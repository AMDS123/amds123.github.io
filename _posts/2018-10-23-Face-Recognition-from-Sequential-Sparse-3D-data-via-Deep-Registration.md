---
layout: post
title: "Face Recognition from Sequential Sparse 3D data via Deep Registration"
date: 2018-10-23 04:58:48
categories: arXiv_CV
tags: arXiv_CV Sparse Face CNN Recognition Face_Recognition
author: Yang Tan, Hongxin Lin, Zelin Xiao, Shengyong Ding, Hongyang Chao
mathjax: true
---

* content
{:toc}

##### Abstract
Previous works have shown that face recognition with high accuracy 3D data is more reliable and insensitive to pose and light variations. Recently, low-cost and portable 3D acquisition techniques like ToF(Time of Flight) and DoE based structured light enable us to access 3D data easily, e.g. via a mobile phone. However, these devices can only provide sparse(limited speckles in structured light system) and noisy 3D data which can not support face recognition directly. In this paper, we aim at achieving high performance face recognition for devices equipped with such modules which is very meaningful in practice as such devices will be very popular. We propose a framework to perform face recognition by fusing a sequence of low-quality 3D data. As 3D data are sparse and noisy which can not be well handled by conventional methods like the ICP algorithm, we design a PointNet-like Deep Registration Network(DRNet) which works with ordered 3D point coordinates while preserving the ability of mining local structures via convolution. Meanwhile we develop a novel loss function to optimize our DRNet based on the quaternion expression which obviously outperforms other widely used functions. For face recognition, we design a deep convolutional network which takes the fused 3D depth-map as input based on AMSoftmax model. Experiments show that our DRNet can achieve rotation error 0.95 degrees and translation error 0.28mm for registration. The face recognition on fused data also achieves rank-1 accuracy 99.2%, FAR-0.001 97.5% on Bosphorus dataset which is comparable with state-of-the-art high-quality data based recognition performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09658](http://arxiv.org/abs/1810.09658)

##### PDF
[http://arxiv.org/pdf/1810.09658](http://arxiv.org/pdf/1810.09658)

