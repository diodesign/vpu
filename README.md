# VPU

The Vulture Processing Unit (VPU) is a soft implementation of a simple vector-math accelerator written in Verilog using [nMigen](https://github.com/m-labs/nmigen).
It is my first attempt at designing a math coprocessor, and should only be used for educational purposes. Consider this a personal experiment.

The VPU is suitable for neural-network inference workloads using 8-bit integer models.

## Todo

This is a work in progress. Here's what needs to be implemented:
* INT8 multiply-and-add unit
* Data fetch
* Data write
* Control registers
* Interrupts
* DMA engine
* Driver software
* SRAM cache
* Probably more...

## Copyright, license, and contact

Copyright &copy; Chris Williams, 2020. See [LICENSE](https://github.com/diodesign/vpu/blob/master/LICENSE) for distribution and use of source code and binaries.

Please [email](mailto:diodesign@tuta.io) me if you have any questions or issues to raise, wish to get involved, or have source to contribute. You can, of course, submit pull requests or raise issues via GitHub. Please include `vpu` in the subject line if you do decide to email.