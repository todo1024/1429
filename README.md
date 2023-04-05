# 1429
缓冲区溢出-CTF-PWN | 完结
### 微:NoBug1024 


课程介绍：

主要讲溢出、常见寄存器、汇编知识、函数调用过程、栈帧、Linux程序保护、突破、ROP（ret2text、ret2shellcode、ret2syscall、ret2Lib）等知识点，使用GDB、IDA、objdump、ROPgadget、pwntools等工具进行学习，通过理论与实践相结合的方式让大家学习PWN更加容易。

课程目录：

第一节：晚安PWN课程介绍 --课程体系，Margin在学习PWN的时候遇到的困惑

第二节：PWN基础知识 --PWN的基本概念，溢出的基础知识，常用寄存器、汇编知识，栈帧以及汇编中函数调用过程。

第三节：Canary保护及突破 – 二进制文件保护方法，Canary保护原理和突破，GCC命令学习，GDB命令学习。

第四节：ROP-Ret2Text --BSS段、Data段、Text段、rodata段讲解，objdump常见的使用方法，如何通过溢出将程序返回地址修改为text段内容。

第五节：ROP-Ret2ShellCode --什么是shellcode，如果使用溢出执行shellcode

第六节：ROP-Ret2Syscall --系统调用函数、函数调用号，如何用Gadget技术来拼接栈空间内容，达到获取shell的目的。

第七节：ROP-Ret2Libc --如何计算Libc的基地址，如何计算函数的地址？如何获取shell？

