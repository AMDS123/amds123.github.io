---
layout: post
title: "Convolutional Neural Networks on 3D Surfaces Using Parallel Frames"
date: 2018-08-15 02:39:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Classification Deep_Learning
author: Hao Pan, Shilin Liu, Yang Liu, Xin Tong
mathjax: true
---

* content
{:toc}

##### Abstract
We extend Convolutional Neural Networks (CNNs) on flat and regular domains (e.g. 2D images) to curved surfaces embedded in 3D Euclidean space that are discretized as irregular meshes and widely used to represent geometric data in Computer Vision and Graphics. We define surface convolution on tangent spaces of a surface domain, where the convolution has two desirable properties: 1) the distortion of surface domain signals is locally minimal when being projected to the tangent space, and 2) the translation equi-variance property holds locally, by aligning tangent spaces with the canonical parallel transport that preserves metric. For computation, we rely on a parallel N-direction frame field on the surface that minimizes field variation and therefore is as compatible as possible to and approximates the parallel transport. On the tangent spaces equipped with parallel frames, the computation of surface convolution becomes standard routine. The frames have rotational symmetry which we disambiguate by constructing the covering space of surface induced by the parallel frames and grouping the feature maps into N sets accordingly; convolution is computed on the N branches of the cover space with respective feature maps while the kernel weights are shared. To handle irregular points of a discrete mesh while sharing kernel weights, we make the convolution semi-discrete, i.e. the convolution kernels are polynomial functions, and their convolution with discrete surface points becomes sampling and weighted summation. Pooling and unpooling operations are computed along a mesh hierarchy built through simplification. The presented surface CNNs allow effective deep learning on meshes. We show that for tasks of classification, segmentation and non-rigid registration, surface CNNs using only raw input signals achieve superior performances than previous models using sophisticated input features.

##### Abstract (translated by Google)
我们将平面和规则域（例如2D图像）上的卷积神经网络（CNN）扩展到嵌入3D欧几里德空间中的曲面，这些曲面被离散化为不规则网格并广泛用于表示计算机视觉和图形中的几何数据。我们在表面域的切线空间上定义表面卷积，其中卷积具有两个期望的属性：1）当投影到切线空间时，表面域信号的失真局部最小，以及2）平移等方差属性保持在局部，通过将切线空间与保留度量的规范并行传输对齐。为了计算，我们依赖于表面上的并行N方向帧场，其最小化场变化，因此尽可能地兼容并近似于并行传输。在配备有平行框架的切线空间上，表面卷积的计算成为标准程序。框架具有旋转对称性，我们通过构造由平行框架引起的表面覆盖空间并相应地将特征图分组为N组来消除歧义;在覆盖空间的N个分支上利用相应的特征映射计算卷积，同时共享内核权重。为了在共享核权重的同时处理离散网格的不规则点，我们使卷积半离散，即卷积核是多项式函数，并且它们与离散表面点的卷积变为采样和加权求和。池化和解除操作是通过简化构建的网格层次结构计算的。所呈现的表面CNN允许对网格进行有效的深度学习。我们表明，对于分类，分割和非刚性配准的任务，仅使用原始输入信号的表面CNN比使用复杂输入特征的先前模型实现了优越的性能。

##### URL
[http://arxiv.org/abs/1808.04952](http://arxiv.org/abs/1808.04952)

##### PDF
[http://arxiv.org/pdf/1808.04952](http://arxiv.org/pdf/1808.04952)

