---
layout: post
title: "Recursive Cascaded Networks for Unsupervised Medical Image Registration"
date: 2019-07-29 12:10:03
categories: arXiv_CV
tags: arXiv_CV
author: Shengyu Zhao, Yue Dong, Eric I-Chao Chang, Yan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We present recursive cascaded networks, a general architecture that enables learning deep cascades, for deformable image registration. The proposed architecture is simple in design and can be built on any base network. The moving image is warped successively by each cascade and finally aligned to the fixed image; this procedure is recursive in a way that every cascade learns to perform a progressive deformation for the current warped image. The entire system is end-to-end and jointly trained in an unsupervised manner. In addition, enabled by the recursive architecture, one cascade can be iteratively applied for multiple times during testing, which approaches a better fit between each of the image pairs. We evaluate our method on 3D medical images, where deformable registration is most commonly applied. We demonstrate that recursive cascaded networks achieve consistent, significant gains and outperform state-of-the-art methods. The performance reveals an increasing trend as long as more cascades are trained, while the limit is not observed. Our code will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12353](http://arxiv.org/abs/1907.12353)

##### PDF
[http://arxiv.org/pdf/1907.12353](http://arxiv.org/pdf/1907.12353)

