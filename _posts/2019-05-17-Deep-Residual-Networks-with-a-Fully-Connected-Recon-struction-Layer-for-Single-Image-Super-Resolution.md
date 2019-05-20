---
layout: post
title: "Deep Residual Networks with a Fully Connected Recon-struction Layer for Single Image Super-Resolution"
date: 2019-05-17 16:48:09
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yongliang Tang, Jiashui Huang, Faen Zhang, Weiguo Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep neural networks have achieved impressive performance in terms of both reconstruction accuracy and efficiency for single image super-resolution (SISR). However, the network model of these methods is a fully convolutional neural network, which is limit to exploit the differentiated contextual information over the global region of the input image because of the weight sharing in convolution height and width extent. In this paper, we discuss a new SISR architecture where features are extracted in the low-resolution (LR) space, and then we use a fully connected layer which learns an array of differentiated upsampling weights to reconstruct the desired high-resolution (HR) image from the final obtained LR features. By doing so, we effectively exploit the differentiated contextual information over the whole input image region, whilst maintaining the low computational complexity for the overall SR operations. In addition, we introduce an edge difference constraint into our loss function to preserve edges and texture structures. Extensive experiments validate that our SISR method outperforms the existing state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10143](http://arxiv.org/abs/1805.10143)

##### PDF
[http://arxiv.org/pdf/1805.10143](http://arxiv.org/pdf/1805.10143)

