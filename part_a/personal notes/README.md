# Digging into ```runtasks_ref_linux``` file
- command: ```file```

![Screenshot 2024-10-18 102253](https://github.com/user-attachments/assets/62b384a8-783f-4515-9706-74c0c62369ba)

- ChatGPT:
  - ELF 64-bit LSB pie executable: It's a 64-bit ELF executable in little-endian format. The "pie" means Position Independent Executable, which is a security feature allowing the program to be loaded at random memory addresses.
  - x86-64: It's intended for 64-bit x86 architecture.
  - version 1 (GNU/Linux): It's compiled for Linux.
  - dynamically linked: This executable relies on external libraries (shared objects) at runtime.
  - interpreter /lib64/ld-linux-x86-64.so.2: The dynamic linker/loader responsible for loading the shared libraries at runtime.
  - BuildID[sha1]=bluhbluhbluh: A unique identifier of the binary build based on SHA-1 hash.
  - for GNU/Linux 3.2.0: It was compiled for a Linux system with kernel version 3.2.0 or newer.
  - not stripped: The binary still includes symbol information, which can be useful for debugging.
  
