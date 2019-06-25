---
layout: post
title: "Efficient and Effective Context-Based Convolutional Entropy Modeling for Image Compression"
date: 2019-06-24 16:26:03
categories: arXiv_CV
tags: arXiv_CV CNN
author: Mu Li, Kede Ma, Jane You, David Zhang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
It has long been understood that precisely estimating the probabilistic structure of natural visual images is crucial for image compression. Despite the remarkable success of recent end-to-end optimized image compression, the latent code representation is assumed to be fully statistically factorized such that the entropy modeling is feasible. Here we describe context-based convolutional networks (CCNs) that exploit statistical redundancies in the codes for improved entropy modeling. We introduce a 3D zigzag coding order together with a 3D code dividing technique to define proper context and to achieve parallel entropy decoding, both of which boil down to place translation-invariant binary masks on convolution filters of CCNs. We demonstrate the power of CCNs for entropy modeling in both lossless and lossy image compression. For the former, we directly apply a CCN to binarized image planes for estimating the Bernoulli distribution of each code. For the latter, the categorical distribution of each code is represented by a discretized mixture of Gaussian distributions, whose parameters are estimated by three CCNs. We jointly optimize the CCN-based entropy model with analysis and synthesis transforms for rate-distortion performance. Experiments on two image datasets show that the proposed lossless and lossy image compression methods based on CCNs generally exhibit better compression performance than existing methods with manageable computational complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10057](http://arxiv.org/abs/1906.10057)

##### PDF
[http://arxiv.org/pdf/1906.10057](http://arxiv.org/pdf/1906.10057)

