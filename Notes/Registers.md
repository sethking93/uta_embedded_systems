# REGISTERS
**Stack Pointer**
- **Main Stack Pointer (MSP)**
- **Process Stack Pointer (PSP)**
**Link Register**
**Program Counter**

3 Status Registers:
1. **Application Program Status Register**
2. **Interrupt Program Status Register**
3. **Execution Program Status Register**

- All three can be accessed through the **Program Status Register (PSR)**
![](https://courses.edx.org/assets/courseware/v1/895132116f5dea1e0236f1a5540e751b/asset-v1:UTAustinX+UT.6.10x+3T2019+type@asset+block/image014.gif)

- **N** bit: set when ALU operation was negative
- **Z** bit: set when result is zero
- **C** bit: (carry) set on unsigned overflow
- **V** bit: signed overflow
- **Q** bit: saturation has occurred