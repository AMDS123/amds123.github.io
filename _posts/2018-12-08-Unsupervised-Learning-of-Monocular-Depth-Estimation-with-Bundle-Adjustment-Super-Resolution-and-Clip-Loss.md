---
layout: post
title: "Unsupervised Learning of Monocular Depth Estimation with Bundle Adjustment, Super-Resolution and Clip Loss"
date: 2018-12-08 18:59:29
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Relation
author: Lipu Zhou, Jiamin Ye, Montiel Abello, Shengze Wang, Michael Kaess
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel unsupervised learning framework for single view depth estimation using monocular videos. It is well known in 3D vision that enlarging the baseline can increase the depth estimation accuracy, and jointly optimizing a set of camera poses and landmarks is essential. In previous monocular unsupervised learning frameworks, only part of the photometric and geometric constraints within a sequence are used as supervisory signals. This may result in a short baseline and overfitting. Besides, previous works generally estimate a low resolution depth from a low resolution impute image. The low resolution depth is then interpolated to recover the original resolution. This strategy may generate large errors on object boundaries, as the depth of background and foreground are mixed to yield the high resolution depth. In this paper, we introduce a bundle adjustment framework and a super-resolution network to solve the above two problems. In bundle adjustment, depths and poses of an image sequence are jointly optimized, which increases the baseline by establishing the relationship between farther frames. The super resolution network learns to estimate a high resolution depth from a low resolution image. Additionally, we introduce the clip loss to deal with moving objects and occlusion. Experimental results on the KITTI dataset show that the proposed algorithm outperforms the state-of-the-art unsupervised methods using monocular sequences, and achieves comparable or even better result compared to unsupervised methods using stereo sequences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03368](http://arxiv.org/abs/1812.03368)

##### PDF
[http://arxiv.org/pdf/1812.03368](http://arxiv.org/pdf/1812.03368)

