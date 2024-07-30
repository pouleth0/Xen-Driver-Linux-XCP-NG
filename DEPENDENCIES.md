# Dependencies

To compile and install `Xen-Driver-Linux-XCP-NG`, you will need the following dependencies:

1. **Compilers and Build Tools:**
   - **GCC:** For compiling the source code.
     - On Ubuntu/Debian: `sudo apt-get install gcc`
     - On CentOS/RHEL: `sudo yum install gcc`

   - **Make:** For automating the build process.
     - On Ubuntu/Debian: `sudo apt-get install make`
     - On CentOS/RHEL: `sudo yum install make`

2. **Kernel Headers and Libraries:**
   - **Kernel Headers:** Required to compile kernel modules.
     - On Ubuntu/Debian: `sudo apt-get install linux-headers-$(uname -r)`
     - On CentOS/RHEL: `sudo yum install kernel-devel`

3. **Kernel Development Tools:**
   - **Build Essentials:** Includes essential tools and libraries for building software.
     - On Ubuntu/Debian: `sudo apt-get install build-essential`
     - On CentOS/RHEL: `sudo yum groupinstall 'Development Tools'`

4. **Debugging and Testing Tools:**
   - **dmesg:** For examining and controlling the kernel message buffer.
     - Generally included in standard Linux distributions.
