# android_vendor_oppo_OP5AA5L1

Vendor blobs for the **Oppo Find X8** (Global) for [LineageOS 23.1](https://lineageos.org/).

> ⚠️ **This repository contains proprietary blobs** extracted from the official ColorOS 16 firmware.  
> Blobs are copyright of OPPO and MediaTek. Use at your own risk.

## Device

| Property | Value |
|---|---|
| **Codename** | `OP5AA5L1` |
| **Model** | CPH2651 |
| **Firmware** | ColorOS 16, BP2A.250605.015 |

## Usage

This repo is automatically used by the device tree. Clone it to:

```bash
git clone https://github.com/CYB3R0ID694/android_vendor_oppo_OP5AA5L1 vendor/oppo/OP5AA5L1 -b lineage-23.1
```

## Generating blobs

From a stock OTA zip:
```bash
# From Android source root
./device/oppo/OP5AA5L1/extract-from-ota.sh /path/to/CPH2651_OTA.zip
```

From a live device (ADB root):
```bash
cd device/oppo/OP5AA5L1
./extract-blobs-adb.sh
```

## License

Proprietary — © OPPO Electronics Corp.
