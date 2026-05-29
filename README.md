# SatSentinel Firmware

Pre-built releases for SatSentinel ESP32-S3 devices.

Browse all releases on the [releases page](https://github.com/Fluxcon/satsentinel-firmware/releases).

## Support

[satsentinel.com](https://satsentinel.com)

<!-- section:base-firmware -->
## Base Firmware

Latest: `base-v0.1.0` — [Download](https://github.com/Fluxcon/satsentinel-firmware/releases/tag/base-v0.1.0)

| File | Description |
|------|-------------|
| `satsentinel.bin` | App firmware — OTA upload via web UI |
| `bootloader.bin` | Bootloader — first flash only |
| `partition-table.bin` | Partition table — first flash only |
| `ota_data_initial.bin` | OTA data init — first flash only |
| `version.txt` | Build version string |
<!-- /section:base-firmware -->

<!-- section:kwehub-firmware -->
## KweHub Firmware

Latest: `kwehub-v0.1.0` — [Download](https://github.com/Fluxcon/satsentinel-firmware/releases/tag/kwehub-v0.1.0)

| File | Description |
|------|-------------|
| `satsentinel.bin` | App firmware — OTA upload via web UI |
| `bootloader.bin` | Bootloader — first flash only |
| `partition-table.bin` | Partition table — first flash only |
| `ota_data_initial.bin` | OTA data init — first flash only |
| `version.txt` | Build version string |
<!-- /section:kwehub-firmware -->

<!-- section:flash-tool -->
## Flash Tool

Latest: `v0.1.0` — [Download](https://github.com/Fluxcon/satsentinel-firmware/releases/tag/v0.1.0)

| File | Platform |
|------|----------|
| `satsentinel-cli-linux.zip` | Linux x64 |
| `satsentinel-cli-macos.zip` | macOS arm64 |
| `satsentinel-cli-win64.zip` | Windows x64 |

### Linux

```bash
unzip satsentinel-cli-linux.zip
./satsentinel-cli
```

### macOS

```bash
unzip satsentinel-cli-macos.zip
xattr -d com.apple.quarantine satsentinel-cli
./satsentinel-cli
```

> The `xattr` command removes the Gatekeeper quarantine flag macOS applies to downloaded files. Only required on first run.

### Windows

Extract `satsentinel-cli-win64.zip` and run `satsentinel-cli.exe`. Windows may show a SmartScreen warning — click **More info -> Run anyway**.
<!-- /section:flash-tool -->
