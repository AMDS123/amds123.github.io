---
layout: post
title: "Ring loss: Convex Feature Normalization for Face Recognition"
date: 2018-02-28 23:13:07
categories: arXiv_CV
tags: arXiv_CV GAN Face Classification Recognition Face_Recognition
author: Yutong Zheng, Dipan K. Pal, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
We motivate and present Ring loss, a simple and elegant feature normalization approach for deep networks designed to augment standard loss functions such as Softmax. We argue that deep feature normalization is an important aspect of supervised classification problems where we require the model to represent each class in a multi-class problem equally well. The direct approach to feature normalization through the hard normalization operation results in a non-convex formulation. Instead, Ring loss applies soft normalization, where it gradually learns to constrain the norm to the scaled unit circle while preserving convexity leading to more robust features. We apply Ring loss to large-scale face recognition problems and present results on LFW, the challenging protocols of IJB-A Janus, Janus CS3 (a superset of IJB-A Janus), Celebrity Frontal-Profile (CFP) and MegaFace with 1 million distractors. Ring loss outperforms strong baselines, matches state-of-the-art performance on IJB-A Janus and outperforms all other results on the challenging Janus CS3 thereby achieving state-of-the-art. We also outperform strong baselines in handling extremely low resolution face matching.

##### Abstract (translated by Google)
我们激励并介绍了Ring loss，这是一种用于深网络的简单优雅的功能归一化方法，旨在增强Softmax等标准损耗功能。我们认为深度特征归一化是监督分类问题的一个重要方面，我们要求模型同样很好地表示每个类在多类问题中的表现。通过硬标准化操作的特征归一化的直接方法导致非凸形式。相反，环损失应用软规范化，它逐渐学习将范数约束为缩放单位圆，同时保留凸性导致更强大的特征。我们将环损应用于大规模人脸识别问题，并在LFW上呈现结果，IJB-A Janus，Janus CS3（IJB-A Janus的超集），名人Frontal-Profile（CFP）和MegaFace干扰项。环流损失优于强劲的基线，与IJB-A Janus的最新性能相匹配，并且胜过Janus CS3的所有其他结果，从而实现最先进的技术。在处理极低分辨率的人脸匹配方面，我们的表现也超越强大的基线。

##### URL
[http://arxiv.org/abs/1803.00130](http://arxiv.org/abs/1803.00130)

##### PDF
[http://arxiv.org/pdf/1803.00130](http://arxiv.org/pdf/1803.00130)

