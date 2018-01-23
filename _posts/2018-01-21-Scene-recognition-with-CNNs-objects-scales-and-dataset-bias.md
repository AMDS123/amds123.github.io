---
layout: post
title: "Scene recognition with CNNs: objects, scales and dataset bias"
date: 2018-01-21 18:18:47
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Recognition
author: Luis Herranz, Shuqiang Jiang, Xiangyang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Since scenes are composed in part of objects, accurate recognition of scenes requires knowledge about both scenes and objects. In this paper we address two related problems: 1) scale induced dataset bias in multi-scale convolutional neural network (CNN) architectures, and 2) how to combine effectively scene-centric and object-centric knowledge (i.e. Places and ImageNet) in CNNs. An earlier attempt, Hybrid-CNN, showed that incorporating ImageNet did not help much. Here we propose an alternative method taking the scale into account, resulting in significant recognition gains. By analyzing the response of ImageNet-CNNs and Places-CNNs at different scales we find that both operate in different scale ranges, so using the same network for all the scales induces dataset bias resulting in limited performance. Thus, adapting the feature extractor to each particular scale (i.e. scale-specific CNNs) is crucial to improve recognition, since the objects in the scenes have their specific range of scales. Experimental results show that the recognition accuracy highly depends on the scale, and that simple yet carefully chosen multi-scale combinations of ImageNet-CNNs and Places-CNNs, can push the state-of-the-art recognition accuracy in SUN397 up to 66.26% (and even 70.17% with deeper architectures, comparable to human performance).

##### Abstract (translated by Google)
由于场景是由部分对象组成的，所以场景的精确识别需要关于场景和对象的知识。在本文中，我们解决了两个相关的问题：1）多尺度卷积神经网络（CNN）体系结构中引起的数据集偏差; 2）如何在CNN中有效地结合以场景为中心和以物体为中心的知识（即Places和ImageNet） 。 Hybrid-CNN的一个早期尝试表明，合并ImageNet并没有多大帮助。在这里，我们提出一个考虑规模的替代方法，从而获得显着的认可收益。通过分析不同尺度的ImageNet-CNNs和Places-CNNs的响应，我们发现两者都在不同的尺度范围内运行，所以在所有尺度上使用相同的网络会导致数据集偏差，导致性能有限。因此，将特征提取器适配于每个特定比例（即比例尺特定的CNN）对于改善识别是至关重要的，因为场景中的对象具有其特定的比例范围。实验结果表明，识别精度高度依赖于规模，简单而精心挑选的ImageNet-CNN和Places-CNN多尺度组合，可以将SUN397中最新的识别精度提高到66.26％ （甚至70.17％具有更深的架构，与人类表现相当）。

##### URL
[https://arxiv.org/abs/1801.06867](https://arxiv.org/abs/1801.06867)

##### PDF
[https://arxiv.org/pdf/1801.06867](https://arxiv.org/pdf/1801.06867)

