# swerve

A suckless-inspired UNIX-like operating system for i386.

## Features

* A basic memory allocator
* A RS-232 driver and VGA text mode driver

## Prerequisites for building

* GNU Binutils 2.32+
* GCC 9.1+ (only C support is necessary)
* GNU Make
* A POSIX shell (`dash`, `bash`)
* fdisk
* GNU GRUB
* QEMU

## Building

1. Build and install the toolchain to your $PATH: `./toolchain/build-toolchain.sh -j3` (note: replace the 3 with the number of cores you have plus 1)
1. Run `make`

## Run in QEMU

1. Run `make run-qemu`

## Build GRUB image

1. Run `make grub-image`
