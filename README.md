# Xen-Driver-Linux-XCP-NG

## Descrição

`Xen-Driver-Linux-XCP-NG` is a driver for the Xen Hypervisor, optimized to work with XCP-ng, an open source virtualization platform based on Xen. This project aims to provide improved support for Linux systems running in XCP-ng environments, offering updated drivers and specific features to ensure maximum compatibility and performance..

## Features

- **XCP-ng compatibility:** Full integration with the XCP-ng platform.
- **Linux VM support:** Optimized drivers for Linux virtual machines.
- **Improved performance:** Performance and stability improvements for virtualized environments.
- **Ongoing updates:** Support for the latest kernel and XCP-ng versions.

## Requirements

- **Linux kernel:** Version 5.10 or higher.
- **XCP-ng:** Version 8.2 or higher.
- **Compilers:** GCC 7.4 or higher.
- **Dependencies:** wget, curl an VCC

## Instalação

1. **Clone the repository:**

    ```bash
    git clone https://github.com/pouleth0/Xen-Driver-Linux-XCP-NG.git
    cd Xen-Driver-Linux-XCP-NG
    ```

2. **Install dependencies:**

   Follow the instructions to install the dependencies listed in `DEPENDENCIES.md`.

3. **Compile the driver:**

    ```bash
    make
    ```

4. **Install the driver:**

    ```bash
    sudo make install
    ```

5. **Load the module:**

    ```bash
    sudo modprobe xen_driver
    ```

## Usage

After installation, the driver will be automatically loaded by the system. To check if the module is loaded correctly, run:

```bash
lsmod | grep xen_driver
