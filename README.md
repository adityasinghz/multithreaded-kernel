# Multithreaded Kernel

This repository contains the source code for a multithreaded kernel written in C with some Assembly and Makefile components.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The multithreaded kernel project aims to develop a basic but functional kernel that supports multithreading. This kernel is intended for educational purposes and to provide a foundation for further development. The project showcases key concepts in operating system development, such as thread management, memory management, and interrupt handling.

## Features

- **Multithreading support:** Allows the kernel to handle multiple threads concurrently.
- **Basic system calls:** Provides fundamental system calls for thread management and I/O operations.
- **Memory management:** Implements basic memory allocation and deallocation mechanisms.
- **Interrupt handling:** Manages hardware and software interrupts to ensure proper kernel functioning.

## Installation

To build and run the multithreaded kernel, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/adityasinghz/multithreaded-kernel.git
    cd multithreaded-kernel
    ```

2. **Build the kernel:**
    ```sh
    make
    ```

3. **Run the kernel:**
    Use an emulator like QEMU to run the kernel:
    ```sh
    make run
    ```

## Usage

To use the kernel, you can follow these basic instructions:

- **Boot the kernel:** After building, the kernel can be booted using an emulator.
- **Execute commands:** The kernel provides a simple command interface for testing system calls and thread operations.
- **Develop and test:** You can modify the kernel code and test new features by rebuilding and running it.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For any questions or issues, please open an issue in the repository or contact the repository maintainer.
