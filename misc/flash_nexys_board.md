# Flashing Digilent Nexys2 program

```
$ djtgcfg enum
Found 1 device(s)

Device: Nexys2
    Product Name:   DOnbUsb1 V2.0
    User Name:      Nexys2
    Serial Number:  10054D235581

$ djtgcfg init -d Nexys2
Initializing scan chain...
Found Device ID: f5046093
Found Device ID: 41c22093

Found 2 device(s):
    Device 0: XC3S500E
    Device 1: XCF04S
$ djtgcfg prog -d Nexys2 -i 0 -f /path/to/program.bit
Programming device. Do not touch your board. This may take a few minutes...
Programming succeeded.

```

REF: [How to program Nexys3 FPGA board on Linux using DigilentAdept software: A guide for beginners](https://www.cse.iitb.ac.in/~supratik/courses/cs254/DigilentAdeptBeginnersGuide_TechOverflow.pdf)
