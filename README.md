# Aurora Releases

This public repository contains official Windows release downloads for Aurora.
The development repository and its Git history remain private.

## Downloads

Use the Releases page to download:

- the unsigned Windows x64 installer;
- the portable Windows x64 archive;
- the signed offline update bundle;
- SHA-256 checksums and the signed update manifest;
- the exact corresponding source snapshot for each distributed build.

Windows SmartScreen may warn about the installer because the current builds are
not Authenticode-signed. Verify the files against `SHA256SUMS.txt` before use.

## Source and third-party software

Each binary release includes a version-matched source snapshot. Aurora embeds
Mihomo in the native Windows build; its upstream project is licensed under GNU
GPL version 3. Dependency versions and build instructions are included in the
source snapshot.

This repository is a distribution channel only. It does not contain Aurora's
development history.
