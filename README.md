# Private Galaxy S5 vendor snapshot

This repository preserves the exact extracted CM11-era Galaxy S5 vendor payloads used by Project Crystal's CM10.2 reverse port. Its directory layout is intended to be checked out at `vendor/samsung`:

- `klte-common/`: shared graphics, Wi-Fi, thermal, and common Samsung components.
- `kltetmo/`: T-Mobile radio, QMI, and Bluetooth components.

The source notes and per-tree `SHA256SUMS` identify the inputs. The extracted data came from the pinned TheMuppets Samsung CM11 vendor archive at `80299199ecef3dfc99adbae45660de2b0b1ed21a` and firmware build `G900TUVU1ANCH`. This repository does not contain modem partitions, bootloaders, EFS, or device-unique subscriber data. No Verizon-specific vendor snapshot has been recovered yet.

Keep this repository private. The main Project Crystal source repository contains the extraction inventories and scripts, so a developer can instead extract locally from a compatible firmware image.
