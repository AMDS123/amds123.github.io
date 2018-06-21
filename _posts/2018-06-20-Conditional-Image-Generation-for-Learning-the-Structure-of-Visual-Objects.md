---
layout: post
title: "Conditional Image Generation for Learning the Structure of Visual Objects"
date: 2018-06-20 16:17:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Detection
author: Tomas Jakab, Ankush Gupta, Hakan Bilen, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of learning landmarks for object categories without any manual annotations. We cast this as the problem of conditionally generating an image of an object from another one, where the images differ by acquisition time and/or viewpoint. The process is aided by providing the generator with a keypoint-like representation extracted from the target image through a tight bottleneck. This encourages the representation to distil information about the object geometry, which changes from source to target, while the appearance, which is shared between the source and target, is read off from the source alone. Conditioning simplifies the generation task significantly, to the point that adopting a simple perceptual loss instead of more sophisticated approaches such as adversarial training is sufficient to learn landmarks. We show that our method is applicable to a large variety of datasets - faces, people, 3D objects, and digits - without any modifications. We further demonstrate that we can learn landmarks from synthetic image deformations or videos, all without manual supervision, while outperforming state-of-the-art unsupervised landmark detectors.

##### Abstract (translated by Google)
在本文中，我们考虑了在没有任何手动注释的情况下学习对象类别的地标的问题。我们将此视为有条件地生成另一个对象的图像的问题，其中图像根据采集时间和/或视点而不同。该过程通过向发生器提供通过严密瓶颈从目标图像提取的类似关键点的表示来辅助。这鼓励表示法提取关于对象几何的信息，该信息从源变为目标，而源和目标之间共享的外观仅从源读取。适应显着简化了生成任务，直到采用简单的感知损失而不是更复杂的方法（如对抗训练）足以学习地标。我们显示我们的方法适用于各种各样的数据集 - 面孔，人员，3D对象和数字 - 没有任何修改。我们进一步证明，我们可以从合成图像变形或视频中学习地标，所有这些都无需人工监督，同时性能优于最先进的无监督地标检测器。

##### URL
[http://arxiv.org/abs/1806.07823](http://arxiv.org/abs/1806.07823)

##### PDF
[http://arxiv.org/pdf/1806.07823](http://arxiv.org/pdf/1806.07823)

