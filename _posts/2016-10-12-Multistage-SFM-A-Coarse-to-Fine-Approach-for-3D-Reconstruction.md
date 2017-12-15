---
layout: post
title: "Multistage SFM: A Coarse-to-Fine Approach for 3D Reconstruction"
date: 2016-10-12 12:41:47
categories: arXiv_CV
tags: arXiv_CV GAN
author: Rajvi Shah, Aditya Deshpande, P J Narayanan
mathjax: true
---

* content
{:toc}

##### Abstract
Several methods have been proposed for large-scale 3D reconstruction from large, unorganized image collections. A large reconstruction problem is typically divided into multiple components which are reconstructed independently using structure from motion (SFM) and later merged together. Incremental SFM methods are most popular for the basic structure recovery of a single component. They are robust and effective but are strictly sequential in nature. We present a multistage approach for SFM reconstruction of a single component that breaks the sequential nature of the incremental SFM methods. Our approach begins with quickly building a coarse 3D model using only a fraction of features from given images. The coarse model is then enriched by localizing remaining images and matching and triangulating remaining features in subsequent stages. These stages are made efficient and highly parallel by leveraging the geometry of the coarse model. Our method produces similar quality models as compared to incremental SFM methods while being notably fast and parallel.

##### Abstract (translated by Google)
已经提出了几种从大型无组织图像集合中进行大规模三维重建的方法。一个大型的重建问题通常被分成多个部分，这些部分利用运动结构（SFM）独立重建，然后合并在一起。增量SFM方法在单个组件的基本结构恢复中是最流行的。它们是健壮有效的，但是在本质上是严格顺序的。我们提出了一个单一组件的SFM重构的多阶段方法，它打破了增量式SFM方法的顺序性。我们的方法始于快速建立一个粗糙的三维模型，只使用一部分来自给定图像的特征。然后通过定位剩余的图像并在随后的阶段匹配和三角测量剩余的特征来丰富粗糙模型。通过利用粗糙模型的几何结构，使这些阶段高效且高度平行。我们的方法与增量式SFM方法相比产生了类似的质量模型，而且速度和速度都非常快。

##### URL
[https://arxiv.org/abs/1512.06235](https://arxiv.org/abs/1512.06235)

##### PDF
[https://arxiv.org/pdf/1512.06235](https://arxiv.org/pdf/1512.06235)

