# yt6801 Linux Driver — LoongArch (loong64)

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

Pre-built kernel modules (`yt6801.ko`) of the **yt6801** Ethernet NIC driver from [裕太微电子 (Motorcomm)](https://www.motor-comm.com) for the **LoongArch (loong64)** architecture on **Debian 14 (deb14)**.

## Overview

- **Driver:** yt6801 Linux Driver v1.0.33
- **Vendor:** 裕太微电子 (Motorcomm / Yutai Microelectronics)
- **Source:** [yt6801-linux-driver-1.0.33.zip](1.0.33/yt6801-linux-driver-1.0.33.zip)
- **Target Platform:** LoongArch 64-bit (loong64), Debian 14

## Supported Kernels

| Kernel Version         | Module Path                                                                          | Module Size  | SHA256                                                             |
|------------------------|--------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------|
| `7.0.13+deb14-loong64` | [1.0.33/7.0.13+deb14-loong64/yt6801.ko.xz](1.0.33/7.0.13+deb14-loong64/yt6801.ko.xz) | ~1.3 MB (xz) | `1218a04e264b74beaa474c2c45e048ab3f9916ef1b3a8f5ccd203c3d8fe4e736` |
| `7.1.3+deb14-loong64`  | [1.0.33/7.1.3+deb14-loong64/yt6801.ko.xz](1.0.33/7.1.3+deb14-loong64/yt6801.ko.xz)   | ~1.3 MB (xz) | `e2ff9dbc9525382deb67261bb1c663e9fd9ef8c449e43484c25158a572794e71` |

## License

Driver source: Proprietary (© 裕太微电子 / Motorcomm).  
This repository: [Apache License 2.0](LICENSE)
