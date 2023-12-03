# oneAPI-SYLC-matrix-multiplication
基于oneAPI的C++/SYCL的矩阵乘法
## Intel oneAPI介绍
  对于大多数应用程序开发者来说，使用高级语言进行编程已经成为一种常见的实践。现有的高级语言编译器已经很好地将程序开发与底层计算机体系结构分离开来，使开发者能够专注于算法和应用程序的开发，而无需深入了解底层处理器指令的操作码。

  随着应用程序复杂性的增加和对计算能力的要求，使用各种硬件加速器（如GPU、FPGA等）成为提高性能和满足实时需求的关键。然而，针对这些硬件加速器进行开发需要深入了解底层硬件体系结构以及特定的开发技巧和工具。这确实需要更专业的知识和经验，超出了普通软件工程师或算法工程师的范畴。

  英特尔oneAPI是一个综合性的软件开发工具集，旨在支持跨多种硬件架构的高性能计算。它提供了一套统一的编程模型和工具，使开发人员能够轻松地利用不同类型的处理器和加速器来加速应用程序的执行。oneAPI的目标是实现代码的可移植性和可扩展性，使开发人员能够更高效地利用现代硬件。

  OneAPI的目标是为开发者提供一致的编程体验，无论使用哪种硬件加速器，都能够以统一的方式进行开发。这使得开发者能够更高效地利用异构计算平台的优势，提高应用程序的性能和效率。oneAPI提供了一套统一的编程模型，使开发人员能够使用相同的代码在不同的硬件上运行应用程序。这种统一性简化了开发过程，减少了维护多个代码版本的复杂性。oneAPI支持跨多种硬件平台的开发。开发人员可以编写一次代码，然后在不同的处理器和加速器上进行优化和执行，从而实现应用程序的高性能。且oneAPI是开放的，并且符合行业标准。它采用了许多开放标准和接口，使开发人员能够与各种硬件和软件组件进行集成。

## 实验环境与准备
  使用英特尔oneAPI Developer Cloud服务，直接利用Developer Cloud平台中的CPU与GPU硬件。<br>
  根据Intel® DevCloud for oneAPI 账号注册快速指南进行注册<br>
  启动 Jupyter 服务<br>
  进入oneAPI_Essentials/02_SYCL_Program_Structure<br>
## 实验过程
先在oneAPI_Essentials/02_SYCL_Program_Structure文件夹下创建一个gaodi.sh文件<br>
![image](https://github.com/gaudi43/oneAPI-SYLC-matrix-multiplication/blob/main/images/sh.png)
在oneAPI_Essentials/02_SYCL_Program_Structure/lab文件夹下创建gaodi.cpp 编写代码<br>



