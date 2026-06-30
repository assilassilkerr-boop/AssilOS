# AssilOS

AssilOS is a minimal 16-bit x86 boot sector operating system built from a modified version of nanochess bootOS. It runs directly from BIOS without requiring any underlying operating system.

## 📸 Screenshot

![AssilOS Running in VirtualBox 6.1](screenshot.png)

## ⚙️ Features

- Boots directly from BIOS (no GRUB, no Linux)
- Written in x86 assembly (NASM)
- Runs in 16-bit real mode
- Lightweight boot sector (512 bytes)
- Custom shell prompt: `$`

## 🚀 How it works

AssilOS is loaded by the BIOS into memory at `0x7C00` and executes directly as a boot sector program. It uses BIOS interrupts for basic input/output operations such as:

- Screen output (`int 0x10`)
- Keyboard input (`int 0x16`)
- Disk access (`int 0x13` if implemented)

## 🧰 Requirements

To build and run AssilOS, you need:

- Windows 7 or later (or Linux distros and MacOS with Wine)
- NASM assembler
- QEMU emulator (or real hardware for advanced users with CSM enabled)
- Make (optional)
- VirtualBox 6.1 or later
Note for newer computers: If your machine uses UEFI, make sure to disable Secure Boot and enable CSM (Legacy Boot) in your BIOS settings, otherwise AssilOS will not boot. 🛠️ Build Instructions

 🛠️ Build Instructions

### Manual build (recommended for Windows 7 users)

```bash
nasm -f bin os.asm -o os.img
