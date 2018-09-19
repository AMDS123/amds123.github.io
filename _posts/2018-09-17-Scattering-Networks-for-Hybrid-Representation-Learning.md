---
layout: post
title: "Scattering Networks for Hybrid Representation Learning"
date: 2018-09-17 06:27:40
categories: arXiv_CV
tags: arXiv_CV GAN CNN Represenation_Learning Classification
author: Edouard Oyallon (CVN, GALEN), Sergey Zagoruyko (ENPC, LIGM), Gabriel Huang (DIRO, MILA), Nikos Komodakis (ENPC, CSD-UOC, LIGM), Simon Lacoste-Julien (DIRO, MILA), Matthew Blaschko (ESAT), Eugene Belilovsky (DIRO, MILA)
mathjax: true
---

* content
{:toc}

##### Abstract
Scattering networks are a class of designed Convolutional Neural Networks (CNNs) with fixed weights. We argue they can serve as generic representations for modelling images. In particular, by working in scattering space, we achieve competitive results both for supervised and unsupervised learning tasks, while making progress towards constructing more interpretable CNNs. For supervised learning, we demonstrate that the early layers of CNNs do not necessarily need to be learned, and can be replaced with a scattering network instead. Indeed, using hybrid architectures, we achieve the best results with predefined representations to-date, while being competitive with end-to-end learned CNNs. Specifically, even applying a shallow cascade of small-windowed scattering coefficients followed by 1$\times$1-convolutions results in AlexNet accuracy on the ILSVRC2012 classification task. Moreover, by combining scattering networks with deep residual networks, we achieve a single-crop top-5 error of 11.4% on ILSVRC2012. Also, we show they can yield excellent performance in the small sample regime on CIFAR-10 and STL-10 datasets, exceeding their end-to-end counterparts, through their ability to incorporate geometrical priors. For unsupervised learning, scattering coefficients can be a competitive representation that permits image recovery. We use this fact to train hybrid GANs to generate images. Finally, we empirically analyze several properties related to stability and reconstruction of images from scattering coefficients.

##### Abstract (translated by Google)
散射网络是一类具有固定权重的设计卷积神经网络（CNN）。我们认为它们可以作为图像建模的通用表示。特别是，通过在散射空间中工作，我们在监督和非监督学习任务中获得了竞争结果，同时在构建更可解释的CNN方面取得了进展。对于监督学习，我们证明CNN的早期层不一定需要学习，而是可以用散射网络代替。实际上，使用混合架构，我们通过迄今为止的预定义表示实现了最佳结果，同时与端到端学习的CNN竞争。具体来说，即使应用浅层次的小窗口散射系数，然后1 $ \ times $ 1-convolutions，也会在ILSVRC2012分类任务中获得AlexNet准确性。此外，通过将散射网络与深度剩余网络相结合，我们在ILSVRC2012上实现了11.4％的单作物前5误差。此外，我们展示了它们可以在CIFAR-10和STL-10数据集的小样本制度中产生出色的性能，超过它们的端到端对应物，通过它们结合几何先验的能力。对于无监督学习，散射系数可以是允许图像恢复的竞争表示。我们使用这个事实来训练混合GAN以生成图像。最后，我们凭经验分析了与散射系数图像的稳定性和重建相关的几个性质。

##### URL
[https://arxiv.org/abs/1809.06367](https://arxiv.org/abs/1809.06367)

##### PDF
[https://arxiv.org/pdf/1809.06367](https://arxiv.org/pdf/1809.06367)

