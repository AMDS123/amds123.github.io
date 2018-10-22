---
layout: post
title: "MRI Reconstruction via Cascaded Channel-wise Attention Network"
date: 2018-10-18 18:37:37
categories: arXiv_CV
tags: arXiv_CV Salient Attention Deep_Learning Quantitative
author: Qiaoying Huang, Dong Yang, Pengxiang Wu, Hui Qu, Jingru Yi, Dimitris Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
We consider an MRI reconstruction problem with input of k-space data at a very low undersampled rate. This can practically benefit patient due to reduced time of MRI scan, but it is also challenging since quality of reconstruction may be compromised. Currently, deep learning based methods dominate MRI reconstruction over traditional approaches such as Compressed Sensing, but they rarely show satisfactory performance in the case of low undersampled k-space data. One explanation is that these methods treat channel-wise features equally, which results in degraded representation ability of the neural network. To solve this problem, we propose a new model called MRI Cascaded Channel-wise Attention Network (MICCAN), highlighted by three components: (i) a variant of U-net with Channel-wise Attention (UCA) module, (ii) a long skip connection and (iii) a combined loss. Our model is able to attend to salient information by filtering irrelevant features and also concentrate on high-frequency information by enforcing low-frequency information bypassed to the final output. We conduct both quantitative evaluation and qualitative analysis of our method on a cardiac dataset. The experiment shows that our method achieves very promising results in terms of three common metrics on the MRI reconstruction with low undersampled k-space data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08229](http://arxiv.org/abs/1810.08229)

##### PDF
[http://arxiv.org/pdf/1810.08229](http://arxiv.org/pdf/1810.08229)

