---
layout: post
title: "Rethinking Monocular Depth Estimation with Adversarial Training"
date: 2018-08-22 19:11:41
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Richard Chen, Faisal Mahmood, Alan Yuille, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular depth estimation is an extensively studied computer vision problem with a vast variety of applications. This work introduces a novel paradigm for monocular depth estimation using deep networks that incorporates adversarial loss. We describe a variety of deep learning architectures that include a structured loss term with conditional generative adversarial networks. In this framework, the generator learns a mapping between an RGB image and its corresponding depth map, while the discriminator learns to distinguish estimated depth maps from ground truth. We benchmark this approach on the NYUv2 and Make3D datasets, and observe that the addition of adversarial training reduces relative error significantly, achieving SOTA performance on Make3D. These results suggest that adversarial training is a powerful technique for improving depth estimation performance of deep networks.

##### Abstract (translated by Google)
单目深度估计是广泛研究的计算机视觉问题，具有广泛的应用。这项工作为使用包含对抗性损失的深度网络的单眼深度估计引入了一种新颖的范例。我们描述了各种深度学习架构，其中包括带有条件生成对抗网络的结构化损失项。在该框架中，生成器学习RGB图像与其对应的深度图之间的映射，而鉴别器学习区分估计的深度图与地面实况。我们在NYUv2和Make3D数据集上对此方法进行了基准测试，并观察到增加对抗训练可显着降低相对误差，从而在Make3D上实现SOTA性能。这些结果表明，对抗训练是一种提高深度网络深度估计性能的强大技术。

##### URL
[http://arxiv.org/abs/1808.07528](http://arxiv.org/abs/1808.07528)

##### PDF
[http://arxiv.org/pdf/1808.07528](http://arxiv.org/pdf/1808.07528)

