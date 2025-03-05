# KFS - Kernel From Scratch

A lightweight, educational operating system kernel developed from scratch. This project aims to provide insights into operating system internals and kernel development.

## Overview

KFS is a minimalistic kernel implementation that demonstrates basic OS concepts:
- Basic memory management
- Simple I/O operations
- Interrupt handling fundamentals

This project serves as both a learning resource and a playground for OS development experimentation.

## Features

- **Bare-metal execution**: Runs directly on hardware without an underlying operating system
- **Basic screen output**: Text-mode display functionality
- **Simple keyboard input**: Basic keyboard driver
- **Interrupt handling**: Basic interrupt setup and management

## Prerequisites

In order to cross-compile you may need to get the appropriat tool, here a link for this purpose.
http://wiki.osdev.org/GCC_Cross-Compiler#Prebuilt_Toolchains


- GCC cross-compiler (targeting i686-elf)
- NASM assembler
- QEMU for testing
- GNU Make

## Building and Running

```bash
# Clone the repository
git clone https://github.com/dgaloiu/kfs.git
cd kfs

# Build the kernel
make

# Run in QEMU
make run
```

## Acknowledgements

- [OSDev Wiki](https://wiki.osdev.org) for resources on OS development
