---
layout: post
title: "Focusing Attention: Towards Accurate Text Recognition in Natural Images"
date: 2017-10-17 04:54:55
categories: arXiv_CV
tags: arXiv_CV Attention Recognition
author: Zhanzhan Cheng, Fan Bai, Yunlu Xu, Gang Zheng, Shiliang Pu, Shuigeng Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text recognition has been a hot research topic in computer vision due to its various applications. The state of the art is the attention-based encoder-decoder framework that learns the mapping between input images and output sequences in a purely data-driven way. However, we observe that existing attention-based methods perform poorly on complicated and/or low-quality images. One major reason is that existing methods cannot get accurate alignments between feature areas and targets for such images. We call this phenomenon "attention drift". To tackle this problem, in this paper we propose the FAN (the abbreviation of Focusing Attention Network) method that employs a focusing attention mechanism to automatically draw back the drifted attention. FAN consists of two major components: an attention network (AN) that is responsible for recognizing character targets as in the existing methods, and a focusing network (FN) that is responsible for adjusting attention by evaluating whether AN pays attention properly on the target areas in the images. Furthermore, different from the existing methods, we adopt a ResNet-based network to enrich deep representations of scene text images. Extensive experiments on various benchmarks, including the IIIT5k, SVT and ICDAR datasets, show that the FAN method substantially outperforms the existing methods.

##### Abstract (translated by Google)
场景文本识别由于其各种应用，一直是计算机视觉领域的热门研究课题。现有技术是基于注意力的编码器 - 解码器框架，其以纯数据驱动的方式学习输入图像和输出序列之间的映射。然而，我们观察到现有的基于关注的方法在复杂的和/或低质量的图像上表现不佳。一个主要的原因是现有的方法不能在这些图像的特征区域和目标之间准确对准。我们称这种现象为“注意力漂移”。针对这一问题，本文提出了采用聚焦注意机制自动缩小漂移注意力的FAN（Focusing Attention Network的缩写）方法。 FAN由两个主要组成部分组成：一个注意力网络（AN），负责识别现有方法中的角色目标;一个聚焦网络（FN），负责通过评估AN是否注意目标区域在图像中。此外，与现有方法不同，我们采用ResNet网络来丰富场景文本图像的深层表示。包括IIIT5k，SVT和ICDAR数据集在内的各种基准的大量实验表明，FAN方法明显优于现有方法。

##### URL
[https://arxiv.org/abs/1709.02054](https://arxiv.org/abs/1709.02054)

##### PDF
[https://arxiv.org/pdf/1709.02054](https://arxiv.org/pdf/1709.02054)

