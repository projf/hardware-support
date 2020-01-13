# Project F Board Support

The following FPGA boards have been tested with Project F:

* [Digilent Nexys Video](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/start) (Xilinx Artix-7 XC7A200T)
* [Digilent Arty A7](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/startl) (Xilinx Artix-7 XC7A35T) - tested using Arty Original [1]
* [Digilent Arty Original](https://reference.digilentinc.com/reference/programmable-logic/arty/start) (Xilinx Artix-7 XC7A35T) - use the Arty A7 contraints file [1]

You can find [constraints](constraints/) files for these boards in this repository.

_[1] The Arty A7 I/O configuration is slightly different from the original Arty, but we don't use any of the affected pins in Project F. You can use the same contraints file with both boards._
