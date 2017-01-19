# edk2-ovmf-x64
Gentoo overlay for TianoCore EDK2  OVMF Binary image. For UEFI boot using QEMU hypervisor

https://fedoraproject.org/wiki/Using_UEFI_with_QEMU

The OVMF binary is necessary to UEFI boot using QEMU.

This ebuild pulls the binary from https://www.kraxel.org/repos/jenkins/edk2/.


This ebuild will be updated automatically (coming soon)

## To use this overlay locally:

Copy `edk2-ovmf-x64.conf` to `/etc/portage/repos.conf/`.
Run these commands:
`mkdir /usr/local/portage/edk2-ovmf-x64/metadata`
`echo 'masters = gentoo' > /usr/local/portage/edk2-ovmf-x64/metadata/layout.conf`


## With `layman`

Coming soon
