---
layout: post
title: "Efficient Semantic Scene Completion Network with Spatial Group Convolution"
date: 2019-07-11 10:29:03
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Prediction
author: Jiahui Zhang, Hao Zhao, Anbang Yao, Yurong Chen, Li Zhang, Hongen Liao
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Spatial Group Convolution (SGC) for accelerating the computation of 3D dense prediction tasks. SGC is orthogonal to group convolution, which works on spatial dimensions rather than feature channel dimension. It divides input voxels into different groups, then conducts 3D sparse convolution on these separated groups. As only valid voxels are considered when performing convolution, computation can be significantly reduced with a slight loss of accuracy. The proposed operations are validated on semantic scene completion task, which aims to predict a complete 3D volume with semantic labels from a single depth image. With SGC, we further present an efficient 3D sparse convolutional network, which harnesses a multiscale architecture and a coarse-to-fine prediction strategy. Evaluations are conducted on the SUNCG dataset, achieving state-of-the-art performance and fast speed. Code is available at https://github.com/zjhthu/SGC-Release.git

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05091](http://arxiv.org/abs/1907.05091)

##### PDF
[http://arxiv.org/pdf/1907.05091](http://arxiv.org/pdf/1907.05091)

