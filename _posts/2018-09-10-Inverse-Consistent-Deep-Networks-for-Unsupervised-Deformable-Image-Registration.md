---
layout: post
title: "Inverse-Consistent Deep Networks for Unsupervised Deformable Image Registration"
date: 2018-09-10 16:30:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Jun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deformable image registration is a fundamental task in medical image analysis, aiming to establish a dense and non-linear correspondence between a pair of images. Previous deep-learning studies usually employ supervised neural networks to directly learn the spatial transformation from one image to another, requiring task-specific ground-truth registration for model training. Due to the difficulty in collecting precise ground-truth registration, implementation of these supervised methods is practically challenging. Although several unsupervised networks have been recently developed, these methods usually ignore the inherent inverse-consistent property (essential for diffeomorphic mapping) of transformations between a pair of images. Also, existing approaches usually encourage the to-be-estimated transformation to be locally smooth via a smoothness constraint only, which could not completely avoid folding in the resulting transformation. To this end, we propose an Inverse-Consistent deep Network (ICNet) for unsupervised deformable image registration. Specifically, we develop an inverse-consistent constraint to encourage that a pair of images are symmetrically deformed toward one another, until both warped images are matched. Besides using the conventional smoothness constraint, we also propose an anti-folding constraint to further avoid folding in the transformation. The proposed method does not require any supervision information, while encouraging the diffeomoprhic property of the transformation via the proposed inverse-consistent and anti-folding constraints. We evaluate our method on T1-weighted brain magnetic resonance imaging (MRI) scans for tissue segmentation and anatomical landmark detection, with results demonstrating the superior performance of our ICNet over several state-of-the-art approaches for deformable image registration. Our code will be made publicly available.

##### Abstract (translated by Google)
可变形图像配准是医学图像分析中的基本任务，旨在建立一对图像之间的密集和非线性对应。以前的深度学习研究通常采用监督神经网络来直接学习从一个图像到另一个图像的空间转换，需要针对模型训练的任务特定的地面实况登记。由于难以收集精确的地面实况登记，这些监督方法的实施实际上具有挑战性。尽管最近已经开发了几种无监督网络，但是这些方法通常忽略了一对图像之间的变换的固有的逆一致性（对于微分同位映射必不可少）。而且，现有方法通常仅通过平滑约束来促使待估计变换局部平滑，这不能完全避免在所得到的变换中折叠。为此，我们提出了一种逆向一致的深度网络（ICNet），用于无监督的可变形图像配准。具体来说，我们开发了一致的约束，以鼓励一对图像彼此对称变形，直到两个扭曲的图像匹配。除了使用传统的平滑约束之外，我们还提出了反折叠约束以进一步避免在变换中折叠。所提出的方法不需要任何监督信息，同时通过所提出的反向一致和反折叠约束来鼓励变换的不同性质。我们评估了我们的T1加权脑磁共振成像（MRI）扫描方法，用于组织分割和解剖标志检测，结果证明了我们的ICNet在几种最先进的可变形图像配准方法中的卓越性能。我们的代码将公开发布。

##### URL
[http://arxiv.org/abs/1809.03443](http://arxiv.org/abs/1809.03443)

##### PDF
[http://arxiv.org/pdf/1809.03443](http://arxiv.org/pdf/1809.03443)

