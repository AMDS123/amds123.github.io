---
layout: post
title: "An Improved Evaluation Framework for Generative Adversarial Networks"
date: 2018-03-20 15:09:09
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Quantitative
author: Shaohui Liu, Yi Wei, Jiwen Lu, Jie Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an improved quantitative evaluation framework for Generative Adversarial Networks on generating domain-specific images, where we improve conventional evaluation methods on two levels: the feature representation and the evaluation metric. Unlike most existing evaluation frameworks which transfer the representation of ImageNet inception model to map images onto the feature space, our framework uses a specialized encoder to acquire fine-grained domain-specific representation. Moreover, for datasets with multiple classes, we propose Class-Aware Frechet Distance (CAFD), which employs a Gaussian mixture model on the feature space to better fit the multi-manifold feature distribution. Experiments and analysis on both the feature level and the image level were conducted to demonstrate improvements of our proposed framework over the recently proposed state-of-the-art FID method. To our best knowledge, we are the first to provide counter examples where FID gives inconsistent results with human judgments. It is shown in the experiments that our framework is able to overcome the shortness of FID and improves robustness. Code will be made available.

##### Abstract (translated by Google)
在本文中，我们提出了一个改进的生成敌对网络定量评估框架来生成特定领域的图像，我们在两个层面改进传统评估方法：特征表示和评估指标。与大多数将ImageNet初始模型的表示转换为将图像映射到特征空间上的现有评估框架不同，我们的框架使用专门的编码器来获取细粒度的领域特定表示。此外，对于具有多个类别的数据集，我们提出了Class-Aware Frechet Distance（CAFD），它在特征空间上采用高斯混合模型来更好地拟合多歧管特征分布。对特征级别和图像级别进行了实验和分析，以证明我们提出的框架相对于最近提出的最新FID方法的改进。据我们所知，我们是第一个提供计数器例子的地方，FID给出了与人类判断不一致的结果。实验表明，我们的框架能够克服FID的短缺并提高鲁棒性。代码将可用。

##### URL
[http://arxiv.org/abs/1803.07474](http://arxiv.org/abs/1803.07474)

##### PDF
[http://arxiv.org/pdf/1803.07474](http://arxiv.org/pdf/1803.07474)

