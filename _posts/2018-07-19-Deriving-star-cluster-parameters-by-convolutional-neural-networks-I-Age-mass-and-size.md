---
layout: post
title: "Deriving star cluster parameters by convolutional neural networks. I. Age, mass, and size"
date: 2018-07-19 22:50:41
categories: arXiv_CV
tags: arXiv_CV Survey CNN Inference Classification Detection
author: J. Bialopetravi&#x10d;ius, D. Narbutis, V. Vansevi&#x10d;ius
mathjax: true
---

* content
{:toc}

##### Abstract
Context. Convolutional neural networks (CNNs) are proven to perform fast classification and detection on natural images and have potential to infer astrophysical parameters on the exponentially increasing amount of sky survey imaging data. The inference pipeline can be trained either from real human-annotated data or simulated mock observations. Up to now star cluster analysis was based on integral or individual resolved stellar photometry. This limits the amount of information that can be extracted from cluster images. 
 Aims. Develop a CNN based algorithm aimed to simultaneously derive ages, masses, and sizes of star clusters directly from multi-band images. Demonstrate CNN capabilities on low mass semi-resolved star clusters in a low signal-to-noise regime. 
 Methods. A CNN was constructed based on the deep residual network (ResNet) architecture and trained on simulated images of star clusters with various ages, masses, and sizes. To provide realistic backgrounds, M31 star fields taken from the PHAT survey were added to the mock cluster images. 
 Results. The proposed CNN was verified on mock images of artificial clusters and has demonstrated high precision and no significant bias for clusters of ages $\lesssim$3Gyr and masses between 250 and 4,000 ${\rm M_\odot}$. The pipeline is end-to-end starting from input images all the way to the inferred parameters, no hand-coded steps have to be performed - estimates of parameters are provided by the neural network in one inferential step from raw images.

##### Abstract (translated by Google)
语境。卷积神经网络（CNN）被证明可以对自然图像进行快速分类和检测，并且有可能在指数增加的天空测量成像数据量上推断出天体物理参数。可以从真实的人类注释数据或模拟模拟观察来训练推理管道。到目前为止，星团聚类分析基于积分或单个分辨恒星光度测定法。这限制了可以从群集图像中提取的信息量。
 目标。开发基于CNN的算法，旨在直接从多波段图像中同时导出星团的年龄，质量和大小。在低信噪比情况下展示低质量半分辨星团的CNN能力。
 方法。 CNN是基于深度残留网络（ResNet）架构构建的，并且对具有不同年龄，质量和大小的星团的模拟图像进行了训练。为了提供逼真的背景，从PHAT调查中获取的M31星级字段被添加到模拟群集图像中。
 结果。所提出的CNN在人工星团的模拟图像上得到验证，并且已经证明了高精度，并且对于年龄$ \ lesssim $ 3Gyr和质量在250到4,000 $ {$ rm M_ \ odot} $之间的群集没有显着偏差。管道是从输入图像一直到推断参数的端到端，不需要执行手工编码步骤 - 参数的估计由神经网络在原始图像的一个推断步骤中提供。

##### URL
[http://arxiv.org/abs/1807.07658](http://arxiv.org/abs/1807.07658)

##### PDF
[http://arxiv.org/pdf/1807.07658](http://arxiv.org/pdf/1807.07658)

