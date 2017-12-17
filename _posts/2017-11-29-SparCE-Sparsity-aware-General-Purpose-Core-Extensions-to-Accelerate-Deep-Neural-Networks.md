---
layout: post
title: "SparCE: Sparsity aware General Purpose Core Extensions to Accelerate Deep Neural Networks"
date: 2017-11-29 16:42:03
categories: arXiv_CV
tags: arXiv_CV Inference Recognition
author: Sanchari Sen, Shubham Jain, Swagath Venkataramani, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have emerged as the method of choice for solving a wide range of machine learning tasks. The enormous computational demands posed by DNNs have most commonly been addressed through the design of custom accelerators. However, these accelerators are prohibitive in many design scenarios (e.g., wearable devices and IoT sensors), due to stringent area/cost constraints. Accelerating DNNs on these low-power systems, comprising of mainly the general-purpose processor (GPP) cores, requires new approaches. We improve the performance of DNNs on GPPs by exploiting a key attribute of DNNs, i.e., sparsity. We propose Sparsity aware Core Extensions (SparCE)- a set of micro-architectural and ISA extensions that leverage sparsity and are minimally intrusive and low-overhead. We dynamically detect zero operands and skip a set of future instructions that use it. Our design ensures that the instructions to be skipped are prevented from even being fetched, as squashing instructions comes with a penalty. SparCE consists of 2 key micro-architectural enhancements- a Sparsity Register File (SpRF) that tracks zero registers and a Sparsity aware Skip Address (SASA) table that indicates instructions to be skipped. When an instruction is fetched, SparCE dynamically pre-identifies whether the following instruction(s) can be skipped and appropriately modifies the program counter, thereby skipping the redundant instructions and improving performance. We model SparCE using the gem5 architectural simulator, and evaluate our approach on 6 image-recognition DNNs in the context of both training and inference using the Caffe framework. On a scalar microprocessor, SparCE achieves 19%-31% reduction in application-level. We also evaluate SparCE on a 4-way SIMD ARMv8 processor using the OpenBLAS library, and demonstrate that SparCE achieves 8%-15% reduction in the application-level execution time.

##### Abstract (translated by Google)
深度神经网络（DNN）已经成为解决广泛的机器学习任务的首选方法。 DNN带来的巨大计算需求通常是通过定制加速器的设计来解决的。然而，由于严格的面积/成本限制，这些加速器在许多设计场景（例如，可穿戴设备和IoT传感器）中是禁止的。在主要由通用处理器（GPP）内核组成的这些低功耗系统上加速DNN需要新的方法。我们通过利用DNN的关键属性（即，稀疏性）来提高GPN上的DNN的性能。我们提出了Sparsity了解核心扩展（SparCE） - 一组微观架构和ISA扩展，利用稀疏性，最小侵入和低开销。我们动态检测零操作数，并跳过一组使用它的未来指令。我们的设计确保指令被跳过，甚至被取走，因为挤压指令带来了惩罚。 SparCE由2个关键的微架构增强组成 -  Sparsity寄存器文件（SpRF）跟踪零寄存器和Sparsity的跳转地址（SASA）表，指示要跳过的指令。当获取指令时，SparCE动态地预先识别是否可以跳过下面的指令并适当修改程序计数器，从而跳过冗余指令并提高性能。我们使用gem5架构模拟器对SparCE进行建模，并在使用Caffe框架进行训练和推理的情况下对6个图像识别DNN进行评估。在标量微处理器上，SparCE在应用程序级别上实现了19％-31％的降低。我们还使用OpenBLAS库在4路SIMD ARMv8处理器上评估SparCE，并证明SparCE在应用程序级执行时间中实现了8％-15％的降低。

##### URL
[https://arxiv.org/abs/1711.06315](https://arxiv.org/abs/1711.06315)

##### PDF
[https://arxiv.org/pdf/1711.06315](https://arxiv.org/pdf/1711.06315)

