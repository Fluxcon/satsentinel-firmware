# SatSentinel Firmware

Pre-built releases for SatSentinel ESP32-S3 devices.

Browse all releases on the [releases page](https://github.com/Fluxcon/satsentinel-firmware/releases).

<!-- section:base-firmware -->
## Base Firmware

Latest: `base-v1.0.0-alpha` — [Download](https://github.com/Fluxcon/satsentinel-firmware/releases/tag/base-v1.0.0-alpha)

| File | Description |
|------|-------------|
| `satsentinel.bin` | App firmware — OTA upload via web UI |
| `bootloader.bin` | Bootloader — first flash only |
| `partition-table.bin` | Partition table — first flash only |
| `ota_data_initial.bin` | OTA data init — first flash only |
| `version.txt` | Build version string |
<!-- /section:base-firmware -->

<!-- section:flash-tool -->
## Flash Tool

Latest: `v0.1.0` — [Download](https://github.com/Fluxcon/satsentinel-firmware/releases/tag/v0.1.0)

| File | Platform |
|------|----------|
| `satsentinel-cli-linux` | Linux x64 |
| `satsentinel-cli-macos` | macOS arm64 |
| `satsentinel-cli-win64.exe` | Windows x64 |

### Linux

```bash
chmod +x satsentinel-cli-linux
./satsentinel-cli-linux
```

### macOS

```bash
chmod +x satsentinel-cli-macos
xattr -d com.apple.quarantine satsentinel-cli-macos
./satsentinel-cli-macos
```

> The `xattr` command removes the Gatekeeper quarantine flag macOS applies to downloaded files. Only required on first run.

### Windows

Run `satsentinel-cli-win64.exe` directly. Windows may show a SmartScreen warning — click **More info -> Run anyway**.
<!-- /section:flash-tool -->

## Support

[satsentinel.com](https://satsentinel.com)
