---
layout: post
title: "Direct Visual Odometry using Bit-Planes"
date: 2016-04-04 19:02:45
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Hatem Alismail, Brett Browning, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
Feature descriptors, such as SIFT and ORB, are well-known for their robustness to illumination changes, which has made them popular for feature-based VSLAM\@. However, in degraded imaging conditions such as low light, low texture, blur and specular reflections, feature extraction is often unreliable. In contrast, direct VSLAM methods which estimate the camera pose by minimizing the photometric error using raw pixel intensities are often more robust to low textured environments and blur. Nonetheless, at the core of direct VSLAM is the reliance on a consistent photometric appearance across images, otherwise known as the brightness constancy assumption. Unfortunately, brightness constancy seldom holds in real world applications. In this work, we overcome brightness constancy by incorporating feature descriptors into a direct visual odometry framework. This combination results in an efficient algorithm that combines the strength of both feature-based algorithms and direct methods. Namely, we achieve robustness to arbitrary photometric variations while operating in low-textured and poorly lit environments. Our approach utilizes an efficient binary descriptor, which we call Bit-Planes, and show how it can be used in the gradient-based optimization required by direct methods. Moreover, we show that the squared Euclidean distance between Bit-Planes is equivalent to the Hamming distance. Hence, the descriptor may be used in least squares optimization without sacrificing its photometric invariance. Finally, we present empirical results that demonstrate the robustness of the approach in poorly lit underground environments.

##### Abstract (translated by Google)
诸如SIFT和ORB之类的特征描述符以其对光照变化的鲁棒性而闻名，这使得它们在基于特征的VSLAM \ @中很受欢迎。然而，在低光，低纹理，模糊和镜面反射等成像条件恶化的情况下，特征提取往往是不可靠的。相比之下，通过使用原始像素强度使光度误差最小化来估计相机姿态的直接VSLAM方法通常对低纹理环境和模糊更加稳健。尽管如此，直接VSLAM的核心是依赖于图像上一致的光度测量外观，否则称为亮度恒定假设。不幸的是，在现实世界的应用程序中，亮度恒定性很少。在这项工作中，我们通过将特征描述符合并到直接视觉测距框架中来克服亮度不变性。这种组合产生了一种高效的算法，结合了基于特征的算法和直接方法的优点。也就是说，我们在低质量和光线不足的环境下工作时，可以实现对任意光度变化的稳健性。我们的方法使用了一个高效的二进制描述符，我们称之为位平面，并说明如何将它用于直接方法所需的基于梯度的优化。此外，我们证明位平面之间的平方欧几里德距离相当于汉明距离。因此，描述符可以用于最小二乘优化而不牺牲其光度不变性。最后，我们提出的实证结果证明了在光线暗淡的地下环境中该方法的稳健性。

##### URL
[https://arxiv.org/abs/1604.00990](https://arxiv.org/abs/1604.00990)

##### PDF
[https://arxiv.org/pdf/1604.00990](https://arxiv.org/pdf/1604.00990)

