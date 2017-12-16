---
layout: post
title: "Robust Stereo Feature Descriptor for Visual Odometry"
date: 2017-08-26 05:35:02
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Ehsan Shojaedini, Reza Safabakhsh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple way to utilize stereo camera data to improve feature descriptors. Computer vision algorithms that use a stereo camera require some calculations of 3D information. We leverage this pre-calculated information to improve feature descriptor algorithms. We use the 3D feature information to estimate the scale of each feature. This way, each feature descriptor will be more robust to scale change without significant computations. In addition, we use stereo images to construct the descriptor vector. The SIFT and FREAK descriptors are used to evaluate the proposed method. The scale normalization technique in feature tracking test improves the standard SIFT by 8.75% and improves the standard FREAK by 28.65%. We also use a simple visual odometry algorithm and test it on the KITTI datasets. The stereo FREAK descriptor raises the number of inlier matches by 19% and consequently improves the accuracy of visual odometry by 23%.

##### Abstract (translated by Google)
在本文中，我们提出了一种简单的方法来利用立体相机数据来改善特征描述符。使用立体相机的计算机视觉算法需要一些3D信息的计算。我们利用这个预先计算的信息来改进特征描述符算法。我们使用3D特征信息来估计每个特征的尺度。这样，每个特征描述符将会更加健壮，可以在不进行重要计算的情况下对比例进行缩放。另外，我们使用立体图像来构建描述符向量。 SIFT和FREAK描述符被用来评估所提出的方法。特征跟踪测试中的比例归一化技术将标准SIFT提高了8.75％，将标准FREAK提高了28.65％。我们还使用一个简单的视觉测距算法，并在KITTI数据集上进行测试。立体声FREAK描述符将内部匹配的数量提高了19％，从而将视觉测距的准确性提高了23％。

##### URL
[https://arxiv.org/abs/1708.07933](https://arxiv.org/abs/1708.07933)

##### PDF
[https://arxiv.org/pdf/1708.07933](https://arxiv.org/pdf/1708.07933)

