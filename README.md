# 32 bit Toolchain

Intended host: 64 bit Linux (img_generic-builder)
Intended target: 32 bit Linux

Cmake adapted from: https://github.com/google/boringssl/blob/master/util/32-bit-toolchain.cmake

## Compilers

Apparently GCC toolchains aren't just available for download, so we default to using what we can install from official repositories. To see what this evaluates to, please refer to [the builder image](https://github.com/eons-dev/img_generic-builder).

## How To Use

Use this toolchain with `ebbs . -b cpp --toolchain x86`.
Please refer to the [ebbs documentation](https://github.com/eons-dev/bin_ebbs) for more info.