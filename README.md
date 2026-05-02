<div align="center">
  <img src="./images/logo.png" width="280" />
</div>

[ English | [简体中文](README_zh.md) ]

# NeoOS Kernel

> 本项目是基于 [vivo BlueOS](https://github.com/vivoblueos/kernel) 内核衍生的开发项目，采用 Apache License 2.0 开源协议。

NeoOS kernel is written in Rust, featuring security, lightweight, and generality. It is compatible with POSIX interfaces and supports Rust's standard library.

## Origin and License

This project is a derivative work based on the **vivo BlueOS** kernel project. The original BlueOS kernel was developed by vivo Mobile Communication Co., Ltd. and licensed under Apache License 2.0.

This project continues to be licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

For copyright acknowledgments and third-party component attributions, see the [NOTICE](NOTICE) file.

## Technical Architecture
For details, please visit the BlueOS official website [kernel](https://blueos.vivo.com/kernel) page.

## Board Support
BlueOS kernel currently supports ARM32, ARM64, RISCV32 and RISCV64 chip architectures.
- QEMU platforms are supported for corresponding chip architectures.
- Hardware boards support is currently in progress.

## Repository Overview

| Repository Link | Description |
|----------------|-------------|
| apps | [Shell](https://github.com/vivoblueos/apps_shell) and [examples](https://github.com/vivoblueos/apps_example) developed based on Rust std |
| [book](https://github.com/vivoblueos/book) | Kernel technical documentation and tutorials, including detailed kernel development guides |
| [build](https://github.com/vivoblueos/build) | Project compilation build templates and scripts |
| [kernel](https://github.com/vivoblueos/kernel) | Core kernel repository, including CPU architecture support, system scheduler，sync primitives, async executor, memory management subsystem,  file system, network subsystem, device subsystem, etc |
| [libc](https://github.com/vivoblueos/libc) | BlueOS kernel libc header files, forked from [rust-lang/libc](https://github.com/rust-lang/libc) |
| [librs](https://github.com/vivoblueos/librs) | BlueOS kernel libc implementation based on Rust programming language |

# Getting started with the kernel development
To build and work with the BlueOS kernel, please check following documentations.
- [Prepare basic build environment](https://github.com/vivoblueos/book/blob/main/src/getting-started.md)
- [Build customized Rust toolchain](https://github.com/vivoblueos/book/blob/main/src/build-rust-toolchain.md)
- [Work with the kernel](https://github.com/vivoblueos/book/blob/main/src/build-kernel.md)

# Technical Documentation
For more information about the BlueOS kernel, please refer to [the kernel book](https://vivoblueos.github.io/book/).
