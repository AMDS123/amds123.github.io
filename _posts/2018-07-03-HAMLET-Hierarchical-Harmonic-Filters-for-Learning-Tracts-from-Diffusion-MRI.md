---
layout: post
title: "HAMLET: Hierarchical Harmonic Filters for Learning Tracts from Diffusion MRI"
date: 2018-07-03 10:25:05
categories: arXiv_CV
tags: arXiv_CV
author: Marco Reisert, Volker A. Coenen, Christoph Kaller, Karl Egger, Henrik Skibbe
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose HAMLET, a novel tract learning algorithm, which, after training, maps raw diffusion weighted MRI directly onto an image which simultaneously indicates tract direction and tract presence. The automatic learning of fiber tracts based on diffusion MRI data is a rather new idea, which tries to overcome limitations of atlas-based techniques. HAMLET takes a such an approach. Unlike the current trend in machine learning, HAMLET has only a small number of free parameters HAMLET is based on spherical tensor algebra which allows a translation and rotation covariant treatment of the problem. HAMLET is based on a repeated application of convolutions and non-linearities, which all respect the rotation covariance. The intrinsic treatment of such basic image transformations in HAMLET allows the training and generalization of the algorithm without any additional data augmentation. We demonstrate the performance of our approach for twelve prominent bundles, and show that the obtained tract estimates are robust and reliable. It is also shown that the learned models are portable from one sequence to another.

##### Abstract (translated by Google)
在这项工作中，我们提出了HAMLET，一种新颖的管道学习算法，在训练后，将原始扩散加权MRI直接映射到同时指示管道方向和管道存在的图像上。基于扩散MRI数据的纤维束的自动学习是一个相当新的想法，其试图克服基于图谱的技术的局限性。 HAMLET采取了这样的方法。与机器学习的当前趋势不同，HAMLET只有少量的自由参数HAMLET基于球面张量代数，它允许对问题进行平移和旋转协变处理。 HAMLET基于重复应用卷积和非线性，它们都遵循旋转协方差。 HAMLET中这种基本图像变换的内在处理允许算法的训练和概括，而无需任何额外的数据增加。我们展示了我们的方法对12个突出的捆绑的性能，并表明获得的流域估计是稳健可靠的。还表明，学习的模型可以从一个序列移植到另一个序列。

##### URL
[https://arxiv.org/abs/1807.01068](https://arxiv.org/abs/1807.01068)

##### PDF
[https://arxiv.org/pdf/1807.01068](https://arxiv.org/pdf/1807.01068)

