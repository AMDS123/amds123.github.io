---
layout: post
title: "Spherical U-Net on Cortical Surfaces: Methods and Applications"
date: 2019-04-01 15:18:53
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Fenqiang Zhao, Shunren Xia, Zhengwang Wu, Dingna Duan, Li Wang, Weili Lin, John H Gilmore, Dinggang Shen, Gang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have been providing the state-of-the-art performance for learning-related problems involving 2D/3D images in Euclidean space. However, unlike in the Euclidean space, the shapes of many structures in medical imaging have a spherical topology in a manifold space, e.g., brain cortical or subcortical surfaces represented by triangular meshes, with large inter-subject and intrasubject variations in vertex number and local connectivity. Hence, there is no consistent neighborhood definition and thus no straightforward convolution/transposed convolution operations for cortical/subcortical surface data. In this paper, by leveraging the regular and consistent geometric structure of the resampled cortical surface mapped onto the spherical space, we propose a novel convolution filter analogous to the standard convolution on the image grid. Accordingly, we develop corresponding operations for convolution, pooling, and transposed convolution for spherical surface data and thus construct spherical CNNs. Specifically, we propose the Spherical U-Net architecture by replacing all operations in the standard U-Net with their spherical operation counterparts. We then apply the Spherical U-Net to two challenging and neuroscientifically important tasks in infant brains: cortical surface parcellation and cortical attribute map development prediction. Both applications demonstrate the competitive performance in the accuracy, computational efficiency, and effectiveness of our proposed Spherical U-Net, in comparison with the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00906](http://arxiv.org/abs/1904.00906)

##### PDF
[http://arxiv.org/pdf/1904.00906](http://arxiv.org/pdf/1904.00906)

