# qemu-rpi-kernel
Qemu kernel for emulating Rpi on QEMU

While I was searching the internet about emulating QEMU, most of the guides pointed to link https://xecdesign.com/downloads/linux-qemu/kernel-qemu which is dead as of now.
So making it available on github for someone who would like to use it.
Hope it helps.

This repo contains two kernels.

kernel-qemu-3.10.25-wheezy, which is the original kernel from link https://xecdesign.com/downloads/linux-qemu/kernel-qemu - Works fine with any wheezy image with changes mentioned in wiki.

kernel-qemu-4.1.7-jessie, which is newer kernel compiled compatible with jessie as well as it works well with older wheezy images, build scripts are in tools folder for reference.

Go through wiki page for step by step guide how to emulate raspberry pi on Qemu on any platform (Win, linux or Mac Os)
