## Installation
- Follow this guide to [check your KMI](https://kernelsu.org/guide/installation.html#kmi) and find appropriate kernel from release.
- Use Kernel Flasher (if you already have root) or Recovery (if using aosp based custom rom) to flash the AnyKernel Zip.

## Request Boot Image
You can request a boot image with a specific kernel if you can't use AnyKernel for any reason, follow the instructions below:
- Upload your boot image to bashupload.com or any other place where you can get a direct download link.
- Copy link of a kernel image (the file which has 'Image' at end) from release according to your KMI.
- Create a github issue with the following contents:
  - First line as boot image link.
  - Second line as kernel image link.
  - Add the label 'bootimg'.
- [Example Usage](https://github.com/SomeEmptyBox/GKI_KernelSU_SUSFS/issues/11)

## Additional Resources
- [Kernel FLasher](https://github.com/fatalcoder524/KernelFlasher): Kernel Flasher is an Android app to flash, backup, and restore kernels.
- [SUSFS Module](https://github.com/sidex15/susfs4ksu-module): This module installs userspace helper tools for SUSFS.

## Acknowledgement
- [KernelSU](https://github.com/tiann/KernelSU): A Kernel based root solution for Android.
- [SUSFS4KSU](https://gitlab.com/simonpunk/susfs4ksu): An addon root hiding kernel patches and userspace module for KernelSU.
- [GKI Project](https://android.googlesource.com/kernel/common): A Google project to develop common kernel images for Android.
