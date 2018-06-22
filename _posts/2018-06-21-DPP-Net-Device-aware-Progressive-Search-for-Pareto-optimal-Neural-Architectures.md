---
layout: post
title: "DPP-Net: Device-aware Progressive Search for Pareto-optimal Neural Architectures"
date: 2018-06-21 12:28:37
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Language_Model
author: Jin-Dong Dong, An-Chieh Cheng, Da-Cheng Juan, Wei Wei, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent breakthroughs in Neural Architectural Search (NAS) have achieved state-of-the-art performances in applications such as image classification and language modeling. However, these techniques typically ignore device-related objectives such as inference time, memory usage, and power consumption. Optimizing neural architecture for device-related objectives is immensely crucial for deploying deep networks on portable devices with limited computing resources. We propose DPP-Net: Device-aware Progressive Search for Pareto-optimal Neural Architectures, optimizing for both device-related (e.g., inference time and memory usage) and device-agnostic (e.g., accuracy and model size) objectives. DPP-Net employs a compact search space inspired by current state-of-the-art mobile CNNs, and further improves search efficiency by adopting progressive search (Liu et al. 2017). Experimental results on CIFAR-10 are poised to demonstrate the effectiveness of Pareto-optimal networks found by DPP-Net, for three different devices: (1) a workstation with Titan X GPU, (2) NVIDIA Jetson TX1 embedded system, and (3) mobile phone with ARM Cortex-A53. Compared to CondenseNet and NASNet-A (Mobile), DPP-Net achieves better performances: higher accuracy and shorter inference time on various devices. Additional experimental results show that models found by DPP-Net also achieve considerably-good performance on ImageNet as well.

##### Abstract (translated by Google)
神经建筑搜索（NAS）最近的突破已经在图像分类和语言建模等应用中取得了最先进的表现。但是，这些技术通常会忽略与设备相关的目标，例如推理时间，内存使用情况和功耗。针对设备相关目标优化神经架构对于在具有有限计算资源的便携式设备上部署深度网络非常重要。我们提出DPP-Net：针对帕累托最优神经架构的装置感知渐进式搜索，针对装置相关（例如推断时间和存储器使用）和装置不可知（例如准确度和模型大小）目标两者进行优化。 DPP-Net采用了受当前最先进的移动CNN启发的紧凑型搜索空间，并通过逐步搜索进一步提高了搜索效率（Liu et al。2017）。在CIFAR-10上的实验结果准备证明DPP-Net为三种不同设备找到的帕累托最优网络的有效性：（1）具有Titan X GPU的工作站，（2）NVIDIA Jetson TX1嵌入式系统和（3） ）带ARM Cortex-A53的手机。与CondenseNet和NASNet-A（移动）相比，DPP-Net实现了更好的性能：更高的精度和更短的各种设备推理时间。其他的实验结果表明，DPP-Net发现的模型在ImageNet上也获得了相当不错的性能。

##### URL
[http://arxiv.org/abs/1806.08198](http://arxiv.org/abs/1806.08198)

##### PDF
[http://arxiv.org/pdf/1806.08198](http://arxiv.org/pdf/1806.08198)

