---
layout: post
title: "A Feature-Driven Active Framework for Ultrasound-Based Brain Shift Compensation"
date: 2018-03-20 22:50:37
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jie Luo, Matt Toews, Ines Machado, Sarah Frisken, Miaomiao Zhang, Frank Preiswerk, Alireza Sedghi, Hongyi Ding, Steve Pieper, Polina Golland, Alexandra Golby, Masashi Sugiyama, William M. Wells III
mathjax: true
---

* content
{:toc}

##### Abstract
A reliable Ultrasound (US)-to-US registration method to compensate for brain shift would substantially improve Image-Guided Neurological Surgery. Developing such a registration method is very challenging, due to factors such as missing correspondence in images, the complexity of brain pathology and the demand for fast computation. We propose a novel feature-driven active framework. Here, landmarks and their displacement are first estimated from a pair of US images using corresponding local image features. Subsequently, a Gaussian Process (GP) model is used to interpolate a dense deformation field from the sparse landmarks. Kernels of the GP are estimated by using variograms and a discrete grid search method. If necessary, the user can actively add new landmarks based on the image context and visualization of the uncertainty measure provided by the GP to further improve the result. We retrospectively demonstrate our registration framework as a robust and accurate brain shift compensation solution on clinical data acquired during neurosurgery.

##### Abstract (translated by Google)
一种可靠的超声（美国） - 美国注册方法来弥补脑转移将大大改善图像引导神经外科手术。由于诸如图像缺失对应性，脑病理学复杂性和对快速计算的需求等因素，开发这种注册方法非常具有挑战性。我们提出了一种新颖的功能驱动的主动框架。在这里，首先使用相应的局部图像特征从一对美国图像估计地标和它们的位移。随后，使用高斯过程（GP）模型来从稀疏地标内插稠密变形场。 GP的核心通过使用变差函数和离散网格搜索方法来估计。如果有必要，用户可以根据图像上下文和GP提供的不确定性测量的可视化主动添加新的地标，以进一步改善结果。我们回顾性展示了我们的注册框架，作为神经外科手术过程中获得的临床数据的强大而准确的脑转移补偿解决方案。

##### URL
[http://arxiv.org/abs/1803.07682](http://arxiv.org/abs/1803.07682)

##### PDF
[http://arxiv.org/pdf/1803.07682](http://arxiv.org/pdf/1803.07682)

