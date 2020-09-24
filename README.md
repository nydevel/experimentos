# experimentos

# This project is for education purpose

I earning OS development from this blog https://os.phil-opp.com/

Recomend it!

# Instructions

## Before build
`rustup override set nightly`
`rustup component add rust-src`
`rustup component add llvm-tools-preview`

### Install tool for boot image creation
`cargo install bootimage`

## Main commands

### Build project
`cargo build`

### Build bootimage
`cargo bootimage`

### Run in qemu
`qemu-system-x86_64 -curses -drive format=raw,file=target/x86_64-experiment/debug/bootimage-experimentos.bin`
