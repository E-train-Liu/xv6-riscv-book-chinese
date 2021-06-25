+ [中文](#cn-title)
+ [English](#en-title)

# 《xv6：简易类Unix教学操作系统》中文翻译版 <a id="cn-title"></a>

## 简介

本项目计划将《xv6：简易类Unix教学操作系统》（又称《xv6 book》）一书翻译为中文。目前翻译尚未完成。

由于本项目维护者并非专业翻译人员，错误在所难免，欢迎大家在“Issue”中指出。

## 关于xv6和《xv6 book》

Unix是由贝尔实验室的Ken Thompson、Dennis Ritchie和Douglas Mcllroy开发的知名早期操作系统。Unix V6是其第6版。其代码量少、结构简洁且设计优秀，在操作系统课程的教学中被广泛应用。

然而，Unix V6的目标平台是PDP-11计算机。PDP架构目前已不常见，给教学带来了一定的困难。2006年，麻省理工大学（MIT）的教授Russ Cox、Frans Kaashoek和Robert Morris仿照Unix V6开发了可运行于x86架构上的xv6操作系统。之后，他们编写了《xv6 book》，并将xv6又移植到了RISC-V架构上。2017年，x86架构的xv6项目正式停止维护，后续的更新和教学活动都将围绕RISC-V架构的xv6进行。

本项目最初根据2020版《xv6 book》翻译。若原书后续有更新，本项目也可能计划跟进。

+ MIT课程主页（2020版）：https://pdos.csail.mit.edu/6.S081/2020/index.html
+ 《xv6 book》PDF（2020版）：https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf
+ xv6-riscv的github主页：https://github.com/mit-pdos/xv6-riscv
+ xv6-riscv-book的github主页：https://github.com/mit-pdos/xv6-riscv-book
+ xv6（x86）的github主页：https://github.com/mit-pdos/xv6-public

## 著作权和开源协议

xv6和《xv6 book》的著作权均归MIT的Russ Cox、Frans Kaashoek和Robert Morris教授所有。本项目仅是对《xv6 book》的翻译。

本项目需遵循[CC-BY 4.0协议](https://creativecommons.org/licenses/by/4.0)。使用本项目需恰当署名。同时，使用本翻译版时也需遵守原版xv6和《xv6 book》项目的许可证中的要求。

+ 本项目许可证：[LICENSE](../LICENSE)
+ xv6-riscv许可证：https://github.com/mit-pdos/xv6-riscv/blob/riscv/LICENSE
+ xv6-riscv-book许可证：https://github.com/mit-pdos/xv6-riscv-book/blob/xv6-riscv/LICENSE


---------------------------------------------------


# *xv6: a simple, Unix-like teaching operating system* Chinese Translation <a id="en-title"></a>

## Introduction

Thsi project plan to translate *xv6: a simple, Unix-like teaching operating system* (*xv6 book*) into Chinese. The translation have not been fully finished yet.

Since the maintainers of this project is not professional translators, mistakes are possible. Pointing out them in "Issue" is encouraged.

## About xv6 and *xv6 book*

Unix is a series of well-known early stage operating systems developed by Ken Thompson、Dennis Ritchie and Douglas Mcllroy from Bell Labs. The Unix V6 is its sixth version, which is commonly used in the education of operating system due to its small code amount, consise structure and good design.

However, the target platform of Unix V6 is PDP-11 computers, which are unpopular currently. This causes difficulty to teaching. In 2006, Russ Cox, Frans Kaashoek and Robert Morris from Massachusetts Institute of Technology (MIT) developed xv6 operating system for x86 architecture according to Unix V6. Later, they wrote *xv6 book* and immigrate xv6 to RISC-V architecture. In 2017, xv6 project for x86 stopped to be maintained. Later updating will be applied to the RISC-V version, and teaching will also accord to the new one.

This project is originally translated from the 2020 edition of *xv6 book*. When the original book is modified, this project may also be updated.

+ Course Home Page (2020): https://pdos.csail.mit.edu/6.S081/2020/index.html
+ *xv6 book* PDF (2020): https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf
+ xv6-riscv on github: https://github.com/mit-pdos/xv6-riscv
+ xv6-riscv-book on github: https://github.com/mit-pdos/xv6-riscv-book
+ xv6 (x86) on github: https://github.com/mit-pdos/xv6-public

## Copyright and License

The copyright of xv6 and *xv6 book* both are reserved by Russ Cox, Frans Kaashoek and Robert Morris from MIT. This project is only a translation of *xv6 book*.

This license of this project is [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0). Use of this project requires proper attribution. Additionally, usage of translation should also follows the licenses of xv6 and *xv6 book*.

+ License of this project：[LICENSE](LICENSE)
+ xv6-riscv license：https://github.com/mit-pdos/xv6-riscv/blob/riscv/LICENSE
+ xv6-riscv-book license：https://github.com/mit-pdos/xv6-riscv-book/blob/xv6-riscv/LICENSE