---
layout: post
title: "From Virtual to Real World Visual Perception using Domain Adaptation -- The DPM as Example"
date: 2016-12-29 13:16:22
categories: arXiv_CV
tags: arXiv_CV Detection
author: Antonio M. Lopez, Jiaolong Xu, Jose L. Gomez, David Vazquez, German Ros
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning tends to produce more accurate classifiers than unsupervised learning in general. This implies that training data is preferred with annotations. When addressing visual perception challenges, such as localizing certain object classes within an image, the learning of the involved classifiers turns out to be a practical bottleneck. The reason is that, at least, we have to frame object examples with bounding boxes in thousands of images. A priori, the more complex the model is regarding its number of parameters, the more annotated examples are required. This annotation task is performed by human oracles, which ends up in inaccuracies and errors in the annotations (aka ground truth) since the task is inherently very cumbersome and sometimes ambiguous. As an alternative we have pioneered the use of virtual worlds for collecting such annotations automatically and with high precision. However, since the models learned with virtual data must operate in the real world, we still need to perform domain adaptation (DA). In this chapter we revisit the DA of a deformable part-based model (DPM) as an exemplifying case of virtual- to-real-world DA. As a use case, we address the challenge of vehicle detection for driver assistance, using different publicly available virtual-world data. While doing so, we investigate questions such as: how does the domain gap behave due to virtual-vs-real data with respect to dominant object appearance per domain, as well as the role of photo-realism in the virtual world.

##### Abstract (translated by Google)
监督式学习通常会产生比无监督学习更准确的分类器。这意味着训练数据首选注释。在解决视觉感知挑战时，例如对图像中的某些对象类进行本地化处理时，所涉及的分类器的学习结果是一个实际的瓶颈。原因是，至少，我们必须用上千个图像的边界框框住对象的例子。先验的是，模型关于参数的数量越复杂，则需要更多的注释示例。这个注释任务是由人类的神谕执行的，这最终会导致注释中的不准确和错误（也就是地面真相），因为这个任务本质上是非常麻烦的，有时是模棱两可的。作为另一种选择，我们率先使用虚拟世界来自动和高精度地收集这些注释。然而，由于使用虚拟数据学习的模型必须在现实世界中运行，我们仍然需要执行域适配（DA）。在本章中，我们将重新研究一个可变形的基于零件的模型（DPM）的DA，作为一个虚拟现实世界DA的例子。作为使用案例，我们使用不同的公开可用的虚拟世界数据来解决驾驶员辅助的车辆检测的挑战。在这样做的同时，我们调查了一些问题，比如：由于虚拟与实际数据相对于每个领域的主要对象出现以及虚拟世界中照片现实主义的作用，领域差距是如何表现的。

##### URL
[https://arxiv.org/abs/1612.09134](https://arxiv.org/abs/1612.09134)

##### PDF
[https://arxiv.org/pdf/1612.09134](https://arxiv.org/pdf/1612.09134)

