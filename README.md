# FiRC 

FiRC is a lightweight, custom-built init system (PID 1) designed specifically for **Theta Linux**. Built in C++, it handles core system initialization, process supervision, and signal management.

## 🚀 Features
* **Process Management:** Boots and supervises essential system services.
* **Signal Handling:** Gracefully handles system signals and reaps zombie processes.
* **Configuration Driven:** Reads service configurations directly from `services.conf`.

## 🛠️ Building and Running

### Prerequisites
To compile FiRC, you need a C++ compiler supporting C++17 and `make`.
* On Arch Linux: `sudo pacman -S base-devel`
* On Gentoo: all the tools come preinstalled lol
* On Debian-based distros: sudo apt install make cmake gcc

### Compilation
Thanks to the included Makefile, compiling FiRC is a breeze. Just run:

```bash
make
```
To install
```bash
make install
```
