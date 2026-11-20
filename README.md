# Amorphix

Run **MorphOS** and **AmigaOS 4** on your PC. Amorphix is a polished, VirtualBox-style
manager around an optimized PowerPC emulator — create a machine, point it at your own
install media, and you're on the Ambient or Workbench desktop in minutes.

> You supply your own licensed MorphOS and/or AmigaOS 4. Amorphix ships **no** operating
> system files. See [Getting a license](#you-bring-the-os).

---

## Download

**[Download Amorphix 1.0 for Windows »](../../releases/latest)**

<!-- Build artifact filled in at release: Amorphix-setup-YYYYMMDD-1.0.exe · SHA-256: <hash> -->

A Linux build is also available on the [releases page](../../releases/latest).

## Quick start

1. Install Amorphix and open it.
2. **New** → pick MorphOS or AmigaOS 4, give it RAM and a disk.
3. Insert your MorphOS Live/Install CD image (or let AmigaOS 4 auto-install from your CD).
4. Boot. That's it.

## Features

- **A real manager** — create, clone, import/export and template machines; restore points;
  per-VM settings for CPU, memory, media and networking.
- **AmigaOS 4 auto-install** — hand it your install CD and it sets the system up for you,
  Guest Tools and bridge included.
- **Guest Tools** — a shared folder between your PC and the guest, plus clipboard and clock sync.
- **Media** — a second and third hard disk, CD images, and a Windows folder as a USB stick.
- **3D (experimental)** — an accelerated graphics path for OpenGL/MiniGL inside the guest.
- **Dark mode**, port forwarding, full-screen, and a clean installer.

## You bring the OS

Amorphix is only the machine. The operating systems are commercial products from their
own vendors, and you need a legitimate copy:

- **MorphOS** — buy a registration from the **[MorphOS Team](https://www.morphos-team.net/)**.
  Unregistered MorphOS runs but slows down after a while; a license removes that.
- **AmigaOS 4** — available from Hyperion Entertainment and Amiga dealers.

Amorphix contains no MorphOS, AmigaOS, Kickstart, or vendor driver files, and never will.

## Built on QEMU

Amorphix stands on [QEMU](https://www.qemu.org/), the open-source machine emulator, which
does the PowerPC and hardware emulation. Amorphix adds the manager, the installer, the Guest
Tools, and tuning on top. Huge thanks to the QEMU project and its contributors.

## License

Amorphix is free software, licensed under the **GNU General Public License v2.0** (it is
derived from QEMU). The complete source is in this repository. You may use, study, share and
modify it under the terms of the GPL.

## Support

If Amorphix is useful to you and you'd like to support development, a donation link will
live here. Entirely optional, always appreciated — and please put your money toward a real
MorphOS license first.

---

*Amorphix is an independent project. MorphOS is a trademark of the MorphOS Development Team.
AmigaOS is a trademark of Hyperion Entertainment. Amorphix is not affiliated with, nor endorsed
by, either.*
