# Yuma OS

**Yuma OS** is a fun terminal OS prototype written in C# using [Cosmos](https://cosmosos.github.io/).  
It’s designed for learning, experimenting, and just having fun with a terminal-based OS.

---

## 🖥 Features

- Multi-user login system
- Centered splash and login screens
- Top bar with **Current App** and **Battery**
- Notes and Todo apps
- GitHub app shop for user-made apps
- Keyboard layouts: US / TR
- Terminal resizing
- Neofetch system info
- Clean UI: clears after commands and apps
- Themes: Gray (default), Red, Green, Blue

---

## 🚀 Download & Run

Download the latest ISO from the [Releases page](https://github.com/YOUR_USERNAME/YumaOS/releases).

### Using VirtualBox

1. Open VirtualBox → **New**
2. Name: `Yuma OS`  
   Type: Other → Version: Other/Unknown (32-bit)
3. Memory: 512 MB+
4. Create a virtual hard disk (optional)
5. Start → Select **YumaOS.iso** as boot disk
6. Boot and enjoy!

### Using QEMU

```bash
qemu-system-x86_64 -cdrom YumaOS.iso -m 512
