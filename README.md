# edk2-ovmf-x64
Gentoo overlay for TianoCore EDK2  OVMF Binary image. For UEFI boot using QEMU hypervisor

https://fedoraproject.org/wiki/Using_UEFI_with_QEMU

The OVMF binary is necessary to UEFI boot using QEMU.

This ebuild pulls the binary from https://www.kraxel.org/repos/jenkins/edk2/.


This ebuild will be updated automatically (coming soon)

## To use this overlay locally:

Copy `edk2-ovmf-x64.conf` to `/etc/portage/repos.conf/`.
Run these commands:
```
emaint sync --repo=edk2-ovmf-x64
emerge --ask edk2-ovmf-x64
```

Presently, the version number (date-based) and the build version are not updated automatically in the ebuild.
Coming soon. If it is not installing because th build cannot be found, you may manually update this in the ebuild, or contact me and I will update it.

## With `layman`

Coming soon
