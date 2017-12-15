---
layout: post
title: "Hierarchical Piecewise-Constant Super-regions"
date: 2016-05-19 13:14:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Imanol Luengo, Mark Basham, Andrew P. French
mathjax: true
---

* content
{:toc}

##### Abstract
Recent applications in computer vision have come to heavily rely on superpixel over-segmentation as a pre-processing step for higher level vision tasks, such as object recognition, image labelling or image segmentation. Here we present a new superpixel algorithm called Hierarchical Piecewise-Constant Super-regions (HPCS), which not only obtains superpixels comparable to the state-of-the-art, but can also be applied hierarchically to form what we call n-th order super-regions. In essence, a Markov Random Field (MRF)-based anisotropic denoising formulation over the quantized feature space is adopted to form piecewise-constant image regions, which are then combined with a graph-based split & merge post-processing step to form superpixels. The graph and quantized feature based formulation of the problem allows us to generalize it hierarchically to preserve boundary adherence with fewer superpixels. Experimental results show that, despite the simplicity of our framework, it is able to provide high quality superpixels, and to hierarchically apply them to form layers of over-segmentation, each with a decreasing number of superpixels, while maintaining the same desired properties (such as adherence to strong image edges). The algorithm is also memory efficient and has a low computational cost.

##### Abstract (translated by Google)
最近在计算机视觉中的应用已经严重依赖于超像素过分割作为高级视觉任务的预处理步骤，诸如对象识别，图像标记或图像分割。在这里，我们提出了一种称为分层分段恒定超区域（HPCS）的新型超像素算法，它不仅可以获得与现有技术相媲美的超像素，而且还可以分层应用来形成我们称之为n阶超级区域。实质上，采用基于马尔可夫随机场（MRF）的量化特征空间上的各向异性去噪方法来形成分段恒定的图像区域，然后将其与基于图形的分割和合并后处理步骤结合以形成超像素。基于图形和量化特征的问题的制定允许我们分层次地推广它以保持边界坚持与更少的超像素。实验结果表明，尽管我们的框架简单，它能够提供高质量的超像素，并分层应用它们来形成过度分割的层，每一个都具有减少数量的超像素，同时保持相同的期望属性（例如作为坚持强大的形象边缘）。该算法还具有记忆效率，并具有低计算成本。

##### URL
[https://arxiv.org/abs/1605.05937](https://arxiv.org/abs/1605.05937)

##### PDF
[https://arxiv.org/pdf/1605.05937](https://arxiv.org/pdf/1605.05937)

