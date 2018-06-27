---
layout: post
title: "AirLab: Autograd Image Registration Laboratory"
date: 2018-06-26 11:12:43
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Robin Sandk&#xfc;hler, Christoph Jud, Simon Andermatt, Philippe C. Cattin
mathjax: true
---

* content
{:toc}

##### Abstract
Medical image registration is an active research topic and forms a basis for many medical image analysis tasks. Although image registration is a rather general concept specialized methods are usually required to target a specific registration problem. The development and implementation of such methods has been tough so far as the gradient of the objective has to be computed. Also, its evaluation has to be performed preferably on a GPU for larger images and for more complex transformation models and regularization terms. This hinders researchers from rapid prototyping and poses hurdles to reproduce research results. There is a clear need for an environment which hides this complexity to put the modeling and the experimental exploration of registration methods into the foreground. With the "Autograd Image Registration Laboratory" (AirLab), we introduce an open laboratory for image registration tasks, where the analytic gradients of the objective function are computed automatically and the device where the computations are performed, on a CPU or a GPU, is transparent. It is meant as a laboratory for researchers and developers enabling them to rapidly try out new ideas for registering images and to reproduce registration results which have already been published. AirLab is implemented in Python using PyTorch as tensor and optimization library and SimpleITK for basic image IO. Therefore, it profits from recent advances made by the machine learning community concerning optimization and deep neural network models. 
 The present draft of this paper roughly outlines AirLab with first code snippets and performance analyses. A more exhaustive introduction will follow as a final version soon.

##### Abstract (translated by Google)
医学图像配准是一个活跃的研究课题，是许多医学图像分析任务的基础。虽然图像注册是一个相当普遍的概念，但通常需要专门的方法来针对特定的注册问题。这种方法的发展和实施是非常艰难的，因为目标的梯度必须被计算出来。而且，其评估必须优选在GPU上执行以获得更大的图像以及更复杂的转换模型和正则化术语。这阻碍了研究人员从快速原型设计和构成重现研究成果的障碍。显然需要一个隐藏这种复杂性的环境，以将注册方法的建模和实验性探索置于前台。通过“Autograd图像注册实验室”（AirLab），我们引入了一个开放的图像配准任务实验室，在CPU或GPU上自动计算目标函数的分析梯度并执行计算的设备是透明。它意味着作为研究人员和开发人员的实验室，使他们能够快速尝试注册图像的新想法并复制已发布的注册结果。 AirLab在Python中使用PyTorch作为张量和优化库，SimpleITK用于基本图像IO。因此，它受益于机器学习界关于优化和深度神经网络模型的最新进展。
 本文件的草案大致概述了AirLab的第一个代码片段和性能分析。更详尽的介绍将很快作为最终版本。

##### URL
[http://arxiv.org/abs/1806.09907](http://arxiv.org/abs/1806.09907)

##### PDF
[http://arxiv.org/pdf/1806.09907](http://arxiv.org/pdf/1806.09907)

