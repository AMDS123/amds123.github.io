---
layout: post
title: "Scaling the Scattering Transform: Deep Hybrid Networks"
date: 2017-04-04 06:13:22
categories: arXiv_CV
tags: arXiv_CV
author: Edouard Oyallon (DI-ENS), Eugene Belilovsky (CVN, GALEN), Sergey Zagoruyko (ENPC)
mathjax: true
---

* content
{:toc}

##### Abstract
We use the scattering network as a generic and fixed ini-tialization of the first layers of a supervised hybrid deep network. We show that early layers do not necessarily need to be learned, providing the best results to-date with pre-defined representations while being competitive with Deep CNNs. Using a shallow cascade of 1 x 1 convolutions, which encodes scattering coefficients that correspond to spatial windows of very small sizes, permits to obtain AlexNet accuracy on the imagenet ILSVRC2012. We demonstrate that this local encoding explicitly learns invariance w.r.t. rotations. Combining scattering networks with a modern ResNet, we achieve a single-crop top 5 error of 11.4% on imagenet ILSVRC2012, comparable to the Resnet-18 architecture, while utilizing only 10 layers. We also find that hybrid architectures can yield excellent performance in the small sample regime, exceeding their end-to-end counterparts, through their ability to incorporate geometrical priors. We demonstrate this on subsets of the CIFAR-10 dataset and on the STL-10 dataset.

##### Abstract (translated by Google)
我们使用散射网络作为监督混合深度网络的第一层的通用和固定初始化。我们表明，早期图层不一定需要学习，在与深度CNN竞争的同时提供预定义表示的最佳结果。使用1 x 1卷积的浅层级，编码与极小尺寸的空间窗口相对应的散射系数，可以在imagenet ILSVRC2012上获得AlexNet精度。我们证明这个局部编码明确地学习了不变性w.r.t.旋转。结合使用现代ResNet的散射网络，ILSVRC2012在imagenet ILSVRC2012上实现了11.4％的一次性前5位错误，与Resnet-18架构相媲美，而仅使用10层。我们还发现，混合架构可以在小样本系统中产生出色的性能，超过他们的端对端，通过结合几何先验的能力。我们在CIFAR-10数据集和STL-10数据集的子集上进行演示。

##### URL
[https://arxiv.org/abs/1703.08961](https://arxiv.org/abs/1703.08961)

##### PDF
[https://arxiv.org/pdf/1703.08961](https://arxiv.org/pdf/1703.08961)

