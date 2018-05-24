---
layout: post
title: "Segmentation of Liver Lesions with Reduced Complexity Deep Models"
date: 2018-05-23 15:45:16
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ram Krishna Pandey, Aswin Vasan, A G Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a computationally efficient architecture that learns to segment lesions from CT images of the liver. The proposed architecture uses bilinear interpolation with sub-pixel convolution at the last layer to upscale the course feature in bottle neck architecture. Since bilinear interpolation and sub-pixel convolution do not have any learnable parameter, our overall model is faster and occupies less memory footprint than the traditional U-net. We evaluate our proposed architecture on the highly competitive dataset of 2017 Liver Tumor Segmentation (LiTS) Challenge. Our method achieves competitive results while reducing the number of learnable parameters roughly by a factor of 13.8 compared to the original UNet model.

##### Abstract (translated by Google)
我们提出了一种计算高效的体系结构，可以学习从肝脏的CT图像中分割病灶。所提出的架构在最后一层使用具有亚像素卷积的双线性插值来升级瓶颈架构中的课程特征。由于双线性插值和子像素卷积没有任何可学习的参数，因此我们的整体模型比传统的U网更快，占用的内存更少。我们在2017年肝肿瘤分割（LiTS）挑战竞争激烈的数据集上评估我们的建议架构。与原始的UNet模型相比，我们的方法实现了有竞争力的结果，同时将可学习参数的数量大约减少了13.8倍。

##### URL
[http://arxiv.org/abs/1805.09233](http://arxiv.org/abs/1805.09233)

##### PDF
[http://arxiv.org/pdf/1805.09233](http://arxiv.org/pdf/1805.09233)

