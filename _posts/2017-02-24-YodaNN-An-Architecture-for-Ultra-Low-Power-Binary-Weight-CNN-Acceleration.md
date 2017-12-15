---
layout: post
title: "YodaNN: An Architecture for Ultra-Low Power Binary-Weight CNN Acceleration"
date: 2017-02-24 08:46:12
categories: arXiv_CV
tags: arXiv_CV Face CNN Image_Classification Optimization Classification
author: Renzo Andri, Lukas Cavigelli, Davide Rossi, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have revolutionized the world of computer vision over the last few years, pushing image classification beyond human accuracy. The computational effort of today's CNNs requires power-hungry parallel processors or GP-GPUs. Recent developments in CNN accelerators for system-on-chip integration have reduced energy consumption significantly. Unfortunately, even these highly optimized devices are above the power envelope imposed by mobile and deeply embedded applications and face hard limitations caused by CNN weight I/O and storage. This prevents the adoption of CNNs in future ultra-low power Internet of Things end-nodes for near-sensor analytics. Recent algorithmic and theoretical advancements enable competitive classification accuracy even when limiting CNNs to binary (+1/-1) weights during training. These new findings bring major optimization opportunities in the arithmetic core by removing the need for expensive multiplications, as well as reducing I/O bandwidth and storage. In this work, we present an accelerator optimized for binary-weight CNNs that achieves 1510 GOp/s at 1.2 V on a core area of only 1.33 MGE (Million Gate Equivalent) or 0.19 mm$^2$ and with a power dissipation of 895 {\mu}W in UMC 65 nm technology at 0.6 V. Our accelerator significantly outperforms the state-of-the-art in terms of energy and area efficiency achieving 61.2 TOp/s/W@0.6 V and 1135 GOp/s/MGE@1.2 V, respectively.

##### Abstract (translated by Google)
卷积神经网络（CNN）在过去的几年里彻底改变了计算机视觉的世界，推动了图像分类超越人类的精确度。今天CNN的计算工作需要耗电的并行处理器或GP-GPU。 CNN系统集成加速器最近的发展大大降低了能耗。不幸的是，即使这些高度优化的设备也超出了移动和深度嵌入式应用的功耗范围，并且面临着CNN重量I / O和存储所带来的严峻局限。这样可以防止未来超低功耗物联网终端节点采用CNN进行近传感器分析。最近的算法和理论上的进步使得即使在训练期间将CNN限制为二进制（+ 1 / -1）权重也能够提供有竞争力的分类准确性。这些新发现为算术核心带来了重要的优化机会，消除了昂贵乘法的需要，并减少了I / O带宽和存储。在这项工作中，我们提出了一个针对二进制重量CNNs优化的加速器，其核心区域仅为1.33 MGE（百万门等效）或0.19 mm $ ^ 2 $，在1.2 V时达到1510 GOp / s，功耗为895我们的加速器在能量和面积效率上明显优于61.2 TOp / s / W@0.6 V和1135 GOp / s / MGE @ 1.2 V，分别。

##### URL
[https://arxiv.org/abs/1606.05487](https://arxiv.org/abs/1606.05487)

##### PDF
[https://arxiv.org/pdf/1606.05487](https://arxiv.org/pdf/1606.05487)

