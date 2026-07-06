# Device tree for Samsung Galaxy Tab A9+ (gta9p)

The Samsung Galaxy Tab A9+ (codenamed _gta9p_) is an Android tablet from Samsung's Galaxy Tab A series.
It is powered by the Qualcomm SM6375 (Snapdragon 695) SoC.

## Specifications

| Component | Details |
| --- | --- |
| SoC | Qualcomm SM6375 (Snapdragon 695) |
| CPU | Octa-core (2x2.2 GHz Kryo 660 Gold & 6x1.8 GHz Kryo 660 Silver) |
| GPU | Adreno 619 |
| RAM | 4/6/8 GB |
| Storage | 64/128 GB |
| Display | 11.0" TFT LCD, 1200x1920 |
| Battery | 7040 mAh |
| Bluetooth | 5.3 |
| Wi-Fi | 802.11 a/b/g/n/ac, dual-band |
| NFC | Yes |

## Device tree structure

This device tree follows the LineageOS multi-repo structure for the `gta9p-common` platform.
It is based on the SM6375 (holi) platform and is shared across gta9p device variants.

## Building

```bash
. build/envsetup.sh
lunch lineage_gta9p-userdebug
mka bacon
```

## Kernel

The kernel source is located at `kernel/samsung/sm6375`.

## Vendor blobs

To extract vendor blobs, run:

```bash
./extract-files.sh
```

## License

```
Copyright (C) 2024-2025 The LineageOS Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
