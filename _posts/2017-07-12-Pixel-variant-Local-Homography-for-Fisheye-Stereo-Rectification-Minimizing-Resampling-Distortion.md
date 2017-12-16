---
layout: post
title: "Pixel-variant Local Homography for Fisheye Stereo Rectification Minimizing Resampling Distortion"
date: 2017-07-12 15:50:37
categories: arXiv_CV
tags: arXiv_CV Attention Optimization
author: Dingfu Zhou, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Large field-of-view fisheye lens cameras have attracted more and more researchers' attention in the field of robotics. However, there does not exist a convenient off-the-shelf stereo rectification approach which can be applied directly to fisheye stereo rig. One obvious drawback of existing methods is that the resampling distortion (which is defined as the loss of pixels due to under-sampling and the creation of new pixels due to over-sampling during rectification process) is severe if we want to obtain a rectification with epipolar line (not epipolar circle) constraint. To overcome this weakness, we propose a novel pixel-wise local homography technique for stereo rectification. First, we prove that there indeed exist enough degrees of freedom to apply pixel-wise local homography for stereo rectification. Then we present a method to exploit these freedoms and the solution via an optimization framework. Finally, the robustness and effectiveness of the proposed method have been verified on real fisheye lens images. The rectification results show that the proposed approach can effectively reduce the resampling distortion in comparison with existing methods while satisfying the epipolar line constraint. By employing the proposed method, dense stereo matching and 3D reconstruction for fisheye lens camera become as easy as perspective lens cameras.

##### Abstract (translated by Google)
大视野鱼眼镜头相机在机器人领域受到越来越多的研究人员的关注。但是，目前还没有一种方便的现成立体声矫正方法可以直接应用于鱼眼立体声装置。现有方法的一个明显的缺点是如果我们想要获得一个纠正，重采样失真（定义为由于欠采样造成的像素损失和由于整流过程期间的过采样而产生新像素）是严重的核线（不是极线圆）约束。为了克服这个弱点，我们提出了一种新颖的像素方式的局部单应性立体整形技术。首先，我们证明确实存在足够的自由度来应用像素方式的局部单应性来进行立体整形。然后我们提出一个方法来利用这些自由和通过优化框架的解决方案。最后，本文提出的方法在实际鱼眼镜头图像上的鲁棒性和有效性得到了验证。整改结果表明，该方法在满足核线约束条件下，与现有方法相比，能够有效降低重采样失真。通过采用该方法，鱼眼镜头相机的高密度立体匹配和三维重建变得与透视相机一样容易。

##### URL
[https://arxiv.org/abs/1707.03775](https://arxiv.org/abs/1707.03775)

##### PDF
[https://arxiv.org/pdf/1707.03775](https://arxiv.org/pdf/1707.03775)

