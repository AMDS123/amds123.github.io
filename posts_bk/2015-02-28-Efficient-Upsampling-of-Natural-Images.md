---
layout: post
title: "Efficient Upsampling of Natural Images"
date: 2015-02-28 00:18:39
categories: arXiv_CV
tags: arXiv_CV Salient
author: Chinmay Hegde, Oncel Tuzel, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method of efficient upsampling of a single natural image. Current methods for image upsampling tend to produce high-resolution images with either blurry salient edges, or loss of fine textural detail, or spurious noise artifacts. In our method, we mitigate these effects by modeling the input image as a sum of edge and detail layers, operating upon these layers separately, and merging the upscaled results in an automatic fashion. We formulate the upsampled output image as the solution to a non-convex energy minimization problem, and propose an algorithm to obtain a tractable approximate solution. Our algorithm comprises two main stages. 1) For the edge layer, we use a nonparametric approach by constructing a dictionary of patches from a given image, and synthesize edge regions in a higher-resolution version of the image. 2) For the detail layer, we use a global parametric texture enhancement approach to synthesize detail regions across the image. We demonstrate that our method is able to accurately reproduce sharp edges as well as synthesize photorealistic textures, while avoiding common artifacts such as ringing and haloing. In addition, our method involves no training phase or estimation of model parameters, and is easily parallelizable. We demonstrate the utility of our method on a number of challenging standard test photos.

##### Abstract (translated by Google)
我们提出了一种新颖的单个自然图像高效采样的方法。目前的图像上采样方法倾向于产生高分辨率的图像，其具有模糊的突出边缘，或者精细纹理细节的丢失或者杂散噪声伪像。在我们的方法中，我们通过将输入图像建模为边和细节层的总和，分别对这些层进行操作，并以自动方式合并放大的结果，从而减轻这些影响。我们将上采样后的输出图像表示为非凸能量最小化问题的解，并提出一种求解易行近似解的算法。我们的算法包括两个主要阶段。 1）对于边缘层，我们使用非参数方法通过构建来自给定图像的补丁字典，并且在图像的更高分辨率版本中合成边缘区域。 2）对于细节层，我们使用全局参数纹理增强方法来合成整个图像的细节区域。我们证明，我们的方法能够准确地重现尖锐的边缘以及合成照片级纹理，同时避免常见的文物，如响铃和晕轮。此外，我们的方法不涉及训练阶段或模型参数的估计，并且易于并行化。我们展示了我们的方法在一些具有挑战性的标准测试照片上的效用。

##### URL
[https://arxiv.org/abs/1503.00040](https://arxiv.org/abs/1503.00040)

##### PDF
[https://arxiv.org/pdf/1503.00040](https://arxiv.org/pdf/1503.00040)

