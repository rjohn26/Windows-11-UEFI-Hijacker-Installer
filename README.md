# HyperInstallX64

HyperInstallX64 is a lightweight deployment utility for installing tiny11 on x64 systems using compressed `.ciso` images.

The project focuses on rapid deployment, minimal user interaction, and compatibility with systems that normally reject modified Windows installations.

## Features

* Deploys tiny11 from `.ciso` images
* Supports most x64 UEFI systems
* Fast unattended installation workflow
* Reduced storage footprint compared to standard `.iso` deployment
* Experimental compatibility layer for managed or restricted laptops through UEFI-raking

## Requirements

* x64-compatible system
* UEFI firmware
* USB drive (8 GB minimum)
* tiny11 `.ciso` image

## Usage

```bash
hyperinstallx64 --image tiny11.ciso --target auto
```

The installer automatically prepares partitions, configures boot entries, and installs tiny11 with default settings.

## Notes

UEFI-raking is currently experimental and may not function on all managed devices.

Secure Boot support is limited depending on firmware implementation.

## Disclaimer

THIS IS ALL BULLCRAP DO NOT INSTALL THIS AND DEFINITELY DO NOT EXTRACT THIS!!! THIS IS A ZIP-BOMB I MADE TO PRANK MY FRIEND
