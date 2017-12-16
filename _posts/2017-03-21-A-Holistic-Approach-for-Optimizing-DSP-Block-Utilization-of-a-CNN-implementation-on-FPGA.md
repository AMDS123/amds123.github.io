---
layout: post
title: "A Holistic Approach for Optimizing DSP Block Utilization of a CNN implementation on FPGA"
date: 2017-03-21 17:41:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption OCR CNN Classification
author: Kamel Abdelouahab, Cedric Bourrasset, Maxime Pelcat, François Berry, Jean-Charles Quinton, Jocelyn Serot
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks are becoming the de-facto standard models for image understanding, and more generally for computer vision tasks. As they involve highly parallelizable computations, CNN are well suited to current fine grain programmable logic devices. Thus, multiple CNN accelerators have been successfully implemented on FPGAs. Unfortunately, FPGA resources such as logic elements or DSP units remain limited. This work presents a holistic method relying on approximate computing and design space exploration to optimize the DSP block utilization of a CNN implementation on an FPGA. This method was tested when implementing a reconfigurable OCR convolutional neural network on an Altera Stratix V device and varying both data representation and CNN topology in order to find the best combination in terms of DSP block utilization and classification accuracy. This exploration generated dataflow architectures of 76 CNN topologies with 5 different fixed point representation. Most efficient implementation performs 883 classifications/sec at 256 x 256 resolution using 8% of the available DSP blocks.

##### Abstract (translated by Google)
深度神经网络正在成为图像理解的事实上的标准模型，更普遍的是计算机视觉任务。由于它们涉及高度可并行化的计算，CNN非常适合当前的细粒度可编程逻辑器件。因此，在FPGA上成功实现了多个CNN加速器。遗憾的是，逻辑单元或DSP单元等FPGA资源仍然有限。这项工作提出了一种依靠近似计算和设计空间探索的整体方法来优化FPGA上的CNN实现的DSP块利用率。在Altera Stratix V器件上实现可重新配置的OCR卷积神经网络，同时改变数据表示形式和CNN拓扑结构，以便在DSP模块利用率和分类准确度方面找到最佳组合，对此方法进行了测试。这次探索产生了具有5种不同的固定点表示的76个CNN拓扑的数据流体系结构。最有效的实现方式是使用8％的可用DSP模块以256 x 256分辨率执行883个分类/秒。

##### URL
[https://arxiv.org/abs/1703.09779](https://arxiv.org/abs/1703.09779)

##### PDF
[https://arxiv.org/pdf/1703.09779](https://arxiv.org/pdf/1703.09779)

