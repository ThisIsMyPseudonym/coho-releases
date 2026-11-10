# Simplexity releases

Release builds of Simplexity, a local answer engine. This repository holds
only the published builds and their checksums; it has no source code and
takes no issues or pull requests.

Each release carries the server archive and a `SHA256SUMS` file. The app's
updater downloads from here and checks the archive against `SHA256SUMS`
before installing it.

- **Nightly** releases are marked as pre-releases and built from the latest
  development commit.
- **Stable** releases are a nightly that was checked and then promoted.
