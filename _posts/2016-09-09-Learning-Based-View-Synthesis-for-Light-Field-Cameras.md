---
layout: post
title: "Learning-Based View Synthesis for Light Field Cameras"
date: 2016-09-09 23:33:38
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Nima Khademi Kalantari, Ting-Chun Wang, Ravi Ramamoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
With the introduction of consumer light field cameras, light field imaging has recently become widespread. However, there is an inherent trade-off between the angular and spatial resolution, and thus, these cameras often sparsely sample in either spatial or angular domain. In this paper, we use machine learning to mitigate this trade-off. Specifically, we propose a novel learning-based approach to synthesize new views from a sparse set of input views. We build upon existing view synthesis techniques and break down the process into disparity and color estimation components. We use two sequential convolutional neural networks to model these two components and train both networks simultaneously by minimizing the error between the synthesized and ground truth images. We show the performance of our approach using only four corner sub-aperture views from the light fields captured by the Lytro Illum camera. Experimental results show that our approach synthesizes high-quality images that are superior to the state-of-the-art techniques on a variety of challenging real-world scenes. We believe our method could potentially decrease the required angular resolution of consumer light field cameras, which allows their spatial resolution to increase.

##### Abstract (translated by Google)
随着消费者光场相机的引入，光场成像近来变得普遍。然而，在角度和空间分辨率之间存在内在的折衷，因此，这些相机通常在空间或角度范围中稀疏采样。在本文中，我们使用机器学习来减轻这种折衷。具体来说，我们提出了一种新颖的基于学习的方法来从一组稀疏的输入视图合成新的视图。我们基于现有的视图合成技术，并将其分解为视差和颜色估计组件。我们使用两个连续的卷积神经网络来对这两个分量进行建模，并通过最小化合成和地面真实图像之间的误差来同时训练两个网络。我们使用Lytro Illum摄像机拍摄的光场只显示四个角落的子孔径视图，显示了我们的方法的性能。实验结果表明，我们的方法在各种具有挑战性的现实世界场景中合成优于最先进技术的高质量图像。我们相信我们的方法可能会降低消费者光场相机所需的角度分辨率，从而增加其空间分辨率。

##### URL
[https://arxiv.org/abs/1609.02974](https://arxiv.org/abs/1609.02974)

##### PDF
[https://arxiv.org/pdf/1609.02974](https://arxiv.org/pdf/1609.02974)

