# Single-Cycle-RISC-V

## Description

This is a project that implements a single cycle RISC-V processor.  
It supports the following instructions:

◆ auipc, jal, jalr  
◆ beq, lw, sw  
◆ addi, slti, add, sub  
◆ mul  
◆ srai, slli

## Executing Program

A testbench code (Final_tb.v) and several golden datas are provided.  
The behavior of the chip can be simulated by using the following commands: 
```
ncverilog Final_tb.v +define+leaf +access+r
```
```
ncverilog Final_tb.v +define+fact +access+r
```
```
ncverilog Final_tb.v +define+hw1 +access+r
```
To see the simulated wave form, use nWave:
```
nWave &
```
and read the generated fsdb file.

## Processor Architecture

<p align="center">
<img src="https://github.com/Howard-Liang/Single-Cycle-RISC-V/blob/main/image/architecture.JPG" width=40% height=40%>
</p>

## Authors

Contributors names and contact info

Hao-Wei, Liang (b07502022@ntu.edu.tw) 

Yen-An, Lu (b07501003@ntu.edu.tw)
  
Yu-An, Lin (b06204039@ntu.edu.tw)

