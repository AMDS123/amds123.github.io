---
layout: post
title: "Colour Constancy: Biologically-inspired Contrast Variant Pooling Mechanism"
date: 2017-11-29 17:14:50
categories: arXiv_CV
tags: arXiv_CV
author: Arash Akbarinia, Raquel Gil Rodríguez, C. Alejandro Parraga
mathjax: true
---

* content
{:toc}

##### Abstract
Pooling is a ubiquitous operation in image processing algorithms that allows for higher-level processes to collect relevant low-level features from a region of interest. Currently, max-pooling is one of the most commonly used operators in the computational literature. However, it can lack robustness to outliers due to the fact that it relies merely on the peak of a function. Pooling mechanisms are also present in the primate visual cortex where neurons of higher cortical areas pool signals from lower ones. The receptive fields of these neurons have been shown to vary according to the contrast by aggregating signals over a larger region in the presence of low contrast stimuli. We hypothesise that this contrast-variant-pooling mechanism can address some of the shortcomings of max-pooling. We modelled this contrast variation through a histogram clipping in which the percentage of pooled signal is inversely proportional to the local contrast of an image. We tested our hypothesis by applying it to the phenomenon of colour constancy where a number of popular algorithms utilise a max-pooling step (e.g. White-Patch, Grey-Edge and Double-Opponency). For each of these methods, we investigated the consequences of replacing their original max-pooling by the proposed contrast-variant-pooling. Our experiments on three colour constancy benchmark datasets suggest that previous results can significantly improve by adopting a contrast-variant-pooling mechanism.

##### Abstract (translated by Google)
池化是图像处理算法中无处不在的操作，允许更高级别的进程从感兴趣的区域收集相关的低级特征。目前，max-pooling是计算文献中最常用的操作符之一。然而，由于它仅仅依赖函数的峰值，所以它可能缺乏对异常值的鲁棒性。在灵长类动物的视觉皮层中也存在汇集机制，其中较高皮质区域的神经元汇集来自较低皮层区域的信号。已经显示这些神经元的感受野在对比度较低的刺激下通过在较大区域聚集信号而根据对比度而变化。我们假设这种对比变体池机制可以解决最大池化的一些缺点。我们通过直方图裁剪来模拟这种对比度变化，其中汇集信号的百分比与图像的局部对比度成反比。我们通过将其应用于颜色恒常现象来测试我们的假设，其中一些流行的算法利用最大集中步骤（例如白色补丁，灰色边缘和双重对齐）。对于这些方法中的每一种，我们都调查了通过建议的对比变体池来替换原始最大池的后果。我们在三个颜色恒定性基准数据集上的实验表明，通过采用对比变体池机制，以前的结果可以显着提高。

##### URL
[https://arxiv.org/abs/1711.10968](https://arxiv.org/abs/1711.10968)

