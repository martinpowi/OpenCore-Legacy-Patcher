# What is OpenCore?

This is a sophisticated boot loader used to inject and patch data in memory, instead of on disk. This means we're able to get near-native experience on many unsupported Macs with Metal GPUs. This includes many of the long desired features of other patchers such as:

* System Integrity Protection, FileVault 2, .im4m Secure Boot and Vaulting
* Native OTA OS DELTA updates on all Macs
* Recovery OS, Safe Mode and Single-user Mode booting
* WPA Wifi and Personal Hotspot support

While many PC users from the Hackintosh community are familiar with OpenCore, OpenCore was designed as Mac and PC agnostic ensuring both platforms can use it easily. And with OpenCore Legacy Patcher, we help automate the process making running with OpenCore that much easier.

For advanced troubleshooting, we highly recommend users check out the [OpenCore Patcher Paradise Discord Server](https://discord.gg/rqdPgH8xSN) as this is generally the quickest way to get a hold of us developers and get help from the community.

For those who wish to support this patcher, please see the [Supporting the Patcher page](./DONATE.md)

## Patcher Warnings

Since this patcher tricks macOS into thinking you're running a newer Mac, certain functionality may be broken:

* Boot Camp Assistant.app
  - We recommend following our [guide on getting a UEFI Windows Install working](./WINDOWS.md). Legacy MBR Based installs won't show up in OpenCore.

## How do I get started?

1. The first step is to ensure whether your model is supported. You can check it here:

* [Supported Models](./MODELS.md)

2. [Download and build macOS Installer](./INSTALLER.md)
3. [Run the `OpenCore-Patcher.app`](./BUILD.md)
4. [Reboot and boot OpenCore](./BOOT.md)
