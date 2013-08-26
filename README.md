##Orange-Sys

A simple IA32 OS.

##build

- Using bximage or other tools to get a blank 3.5 inch floppy disk file(name it `a.img `in default).
- mkdir /mnt/floppy
- Run `make image` in 32-bit linux OS.
- Try adding `fno-stack-protector` or `fpack-struct` to CFLAGS if there is any compiling problem. 

##usage

- Get your hard disk partitioned
- Use floppy disk as startup disk
    - Recommand using bochs as VM

##more

View MAKEFILE to get more details
