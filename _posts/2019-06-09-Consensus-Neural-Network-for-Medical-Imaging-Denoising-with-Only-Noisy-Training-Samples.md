---
layout: post
title: "Consensus Neural Network for Medical Imaging Denoising with Only Noisy Training Samples"
date: 2019-06-09 13:37:34
categories: arXiv_CV
tags: arXiv_CV
author: Dufan Wu, Kuang Gong, Kyungsang Kim, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been proved efficient for medical image denoising. Current training methods require both noisy and clean images. However, clean images cannot be acquired for many practical medical applications due to naturally noisy signal, such as dynamic imaging, spectral computed tomography, arterial spin labeling magnetic resonance imaging, etc. In this paper we proposed a training method which learned denoising neural networks from noisy training samples only. Training data in the acquisition domain was split to two subsets and the network was trained to map one noisy set to the other. A consensus loss function was further proposed to efficiently combine the outputs from both subsets. A mathematical proof was provided that the proposed training scheme was equivalent to training with noisy and clean samples when the noise in the two subsets was uncorrelated and zero-mean. The method was validated on Low-dose CT Challenge dataset and NYU MRI dataset and achieved improved performance compared to existing unsupervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03639](http://arxiv.org/abs/1906.03639)

##### PDF
[http://arxiv.org/pdf/1906.03639](http://arxiv.org/pdf/1906.03639)

