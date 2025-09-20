
# RISC-V Reference SoC Tapeout Program VSD

## Tools Installation

#### <ins>Installation instructions:</ins>
### **Oracle virtual machine link**
https://www.virtualbox.org/wiki/Downloads

### **System Requirements**
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

### **TOOL CHECK**

#### <ins>**Yosys Installation**</ins>
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
![Alt Text](Images/yosys_installation.jpeg)

#### <ins>**Iverilog Installation**</ins>
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
![Alt Text](Images/iverilog.png)

#### <ins>**gtkwave**</ins>
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
![Alt Text](Images/gtkwave_installation.jpeg)

