---
layout: post
title: "Feature Distillation: DNN-Oriented JPEG Compression Against Adversarial Examples"
date: 2018-03-14 02:24:59
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Zihao Liu, Qi Liu, Tao Liu, Yanzhi Wang, Wujie Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have achieved remarkable performance in a myriad of realistic applications. However, recent studies show that well-trained DNNs can be easily misled by adversarial examples (AE) -- the maliciously crafted inputs by introducing small and imperceptible input perturbations. Existing mitigation solutions, such as adversarial training and defensive distillation, suffer from expensive retraining cost and demonstrate marginal robustness improvement against the state-of-the-art attacks like CW family adversarial examples. In this work, we propose a novel low-cost "feature distillation" strategy to purify the adversarial input perturbations of AEs by redesigning the popular image compression framework "JPEG". The proposed "feature distillation" wisely maximizes the malicious feature loss of AE perturbations during image compression while suppressing the distortions of benign features essential for high accurate DNN classification. Experimental results show that our method can drastically reduce the success rate of various state-of-the-art AE attacks by ~60% on average for both CIFAR-10 and ImageNet benchmarks without harming the testing accuracy, outperforming existing solutions like default JPEG compression and "feature squeezing".

##### Abstract (translated by Google)
深度神经网络（DNN）在众多实际应用中取得了卓越的性能。然而，最近的研究表明，训练有素的DNN很容易被敌对的例子（AE）误导 - 通过引入小的不可察觉的输入扰动来恶意制作输入。诸如对抗训练和防御性蒸馏之类的现有缓解解决方案受到昂贵的再培训成本的限制，并且针对CW家族对抗性例子等最先进的攻击显示出边际鲁棒性的提高。在这项工作中，我们提出了一种新的低成本“特征升华”策略，通过重新设计流行的图像压缩框架“JPEG”来净化AE的敌对输入扰动。所提出的“特征提取”明智地最大化了图像压缩期间AE干扰的恶意特征损失，同时抑制了高准确DNN分类所必需的良性特征的失真。实验结果表明，我们的方法可以大幅降低CIFAR-10和ImageNet基准测试平均约60％的各种尖端AE攻击的成功率，而不会降低测试精度，优于现有的解决方案，如默认的JPEG压缩和“功能挤压”。

##### URL
[https://arxiv.org/abs/1803.05787](https://arxiv.org/abs/1803.05787)

##### PDF
[https://arxiv.org/pdf/1803.05787](https://arxiv.org/pdf/1803.05787)

