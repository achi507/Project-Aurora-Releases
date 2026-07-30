# Aurora 1.5.0

Aurora 1.5.0 completes the planned Windows feature line.

## Highlights

- Clear connection-state feedback and persistent policy-group folding.
- Visual and YAML configuration editing.
- Local configuration creation and import.
- TUN preflight reporting, startup recovery, and redacted diagnostics.
- Request and response body Rewrite with identity, gzip, deflate, and Brotli.
- Surge-style `$persistentStore` and Quantumult X-style `$prefs`.
- Response scripts and scheduled local automation.
- Signed offline update-bundle import using the picker or drag and drop.

## Downloads

- `Aurora-1.5.0-Setup-x64.exe` — unsigned Windows x64 installer.
- `Aurora-1.5.0-Portable-x64.zip` — unsigned portable build.
- `Aurora-1.5.0-Private-Update-x64.zip` — signed offline update bundle.
- `SHA256SUMS.txt` — checksums for the distributed binaries.
- `update-manifest.json` — signed update metadata.
- `Aurora-1.5.0-Source.zip` — exact source snapshot corresponding to this
  binary build.

The installer is not Authenticode-signed, so Windows may display a SmartScreen
warning. This release remains tagged `v1.5.0` and uses Mihomo `v1.19.28`.
