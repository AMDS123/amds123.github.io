---
layout: post
title: "FD-MobileNet: Improved MobileNet with a Fast Downsampling Strategy"
date: 2018-02-11 15:01:47
categories: arXiv_CV
tags: arXiv_CV Inference
author: Zheng Qin, Zhaoning Zhang, Xiaotao Chen, Yuxing Peng
mathjax: true
---

* content
{:toc}

##### Abstract
We present Fast-Downsampling MobileNet (FD-MobileNet), an efficient and accurate network for very limited computational budgets (e.g., 10-140 MFLOPs). Our key idea is applying an aggressive downsampling strategy to MobileNet framework. In FD-MobileNet, we perform 32$\times$ downsampling within 12 layers, only half the layers in the original MobileNet. This design brings three advantages: (i) It remarkably reduces the computational cost. (ii) It increases the information capacity and achieves significant performance improvements. (iii) It is engineering-friendly and provides fast actual inference speed. Experiments on ILSVRC 2012 and PASCAL VOC 2007 datasets demonstrate that FD-MobileNet consistently outperforms MobileNet and achieves comparable results with ShuffleNet under different computational budgets, for instance, surpassing MobileNet by 5.5% on the ILSVRC 2012 top-1 accuracy and 3.6% on the VOC 2007 mAP under a complexity of 12 MFLOPs. On an ARM-based device, FD-MobileNet achieves 1.11$\times$ inference speedup over MobileNet and 1.82$\times$ over ShuffleNet under the same complexity.

##### Abstract (translated by Google)
我们提供快速下采样MobileNet（FD-MobileNet），这是一个高效且准确的网络，用于非常有限的计算预算（例如10-140 MFLOP）。我们的主要想法是对MobileNet框架应用积极的下采样策略。在FD-MobileNet中，我们在12层内执行32次$ \ times $下采样，只有原始MobileNet中的一半。这种设计带来三个优点：（i）它显着降低了计算成本。 （ii）它增加了信息容量并实现了显着的性能改进。 （iii）工程友好并提供快速的实际推断速度。在ILSVRC 2012和PASCAL VOC 2007数据集上进行的实验表明，FD-MobileNet一直优于MobileNet，并在不同的计算预算下取得与ShuffleNet类似的结果，例如，在ILSVRC 2012上排名第一的精度上超过MobileNet 5.5％，VOC上超过3.6％ 2007年的MAP在12个MFLOP的复杂度下。在基于ARM的设备上，FD-MobileNet在同样的复杂度下，通过MobileNet达到1.11美元/倍的推断加速，在ShuffleNet上达到1.82美元/倍。

##### URL
[http://arxiv.org/abs/1802.03750](http://arxiv.org/abs/1802.03750)

##### PDF
[http://arxiv.org/pdf/1802.03750](http://arxiv.org/pdf/1802.03750)

