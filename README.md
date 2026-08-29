# Copse releases

This repository is the public download and automatic-update host for
[Copse](https://copse.dev), an AI coding workspace for macOS. It contains
signed, Apple-notarized release binaries; the application source remains in its
separate repository.

## Install Copse

Open [Releases](https://github.com/copse-dev/copse-releases/releases) and
download the DMG matching your Mac:

- `arm64.dmg` — Apple silicon (M1 and newer)
- `x64.dmg` — Intel

Open the DMG, drag Copse to Applications, then launch Copse. macOS 26 or newer
is required.

The ZIP, blockmap, and `*-mac.yml` files beside each installer are automatic
update payloads and metadata; a person installing Copse only needs the matching
DMG. `SHA256SUMS` covers every published artifact.

Beta releases are prereleases. Stable releases appear as the repository's
latest release.
