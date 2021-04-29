This repo allows versioned installation of https://github.com/wix/DetoxInstruments using ruby gems/bundler.

To update the version in this repo:

- Remove `Detox Instruments.app/`.
- Unzip a new copy from https://github.com/wix/DetoxInstruments/releases.
- Commit the new version to git, using the URL you downloaded the new version from in the commit message.
- Add a git tag for the new version e.g. "v1.15.12345".
- Update the version (without the "v" prefix) and the git tag (with the "v" prefix) in the Gemfile of the repo using this gem.
