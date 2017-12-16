---
layout: post
title: "An OpenCL Deep Learning Accelerator on Arria 10"
date: 2017-01-13 00:31:15
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: Utku Aydonat, Shane O'Connell, Davor Capalija, Andrew C. Ling, Gordon R. Chiu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural nets (CNNs) have become a practical means to perform vision tasks, particularly in the area of image classification. FPGAs are well known to be able to perform convolutions efficiently, however, most recent efforts to run CNNs on FPGAs have shown limited advantages over other devices such as GPUs. Previous approaches on FPGAs have often been memory bound due to the limited external memory bandwidth on the FPGA device. We show a novel architecture written in OpenCL(TM), which we refer to as a Deep Learning Accelerator (DLA), that maximizes data reuse and minimizes external memory bandwidth. Furthermore, we show how we can use the Winograd transform to significantly boost the performance of the FPGA. As a result, when running our DLA on Intel's Arria 10 device we can achieve a performance of 1020 img/s, or 23 img/s/W when running the AlexNet CNN benchmark. This comes to 1382 GFLOPs and is 10x faster with 8.4x more GFLOPS and 5.8x better efficiency than the state-of-the-art on FPGAs. Additionally, 23 img/s/W is competitive against the best publicly known implementation of AlexNet on nVidia's TitanX GPU.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成为执行视觉任务的一种实用手段，特别是在图像分类领域。众所周知，FPGA能够有效地执行卷积，然而，最近在FPGA上运行CNN的努力已经显示出比诸如GPU的其他器件有限的优势。由于FPGA器件上的外部存储器带宽有限，FPGA上的以前方法通常会受到存储器的限制。我们展示了一种用OpenCL（TM）编写的新颖架构，我们称之为深度学习加速器（DLA），可最大限度地提高数据重用性并最大限度地减少外部存储器带宽。此外，我们展示了如何使用Winograd变换来显着提升FPGA的性能。因此，在英特尔Arria 10设备上运行我们的DLA时，运行AlexNet CNN基准测试时，我们可以达到1020 img / s或23 img / s / W的性能。这与1382 GFLOP相比，速度提高了10倍，比现有技术的FPGA高出8.4倍，GFLOPS和5.8倍的效率。此外，23 img / s / W与nVidia的TitanX GPU上众所周知的AlexNet的最佳实现竞争。

##### URL
[https://arxiv.org/abs/1701.03534](https://arxiv.org/abs/1701.03534)

##### PDF
[https://arxiv.org/pdf/1701.03534](https://arxiv.org/pdf/1701.03534)

