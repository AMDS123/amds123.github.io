---
layout: post
title: "Image-Dependent Local Entropy Models for Learned Image Compression"
date: 2018-05-31 02:32:48
categories: arXiv_CV
tags: arXiv_CV
author: David Minnen, George Toderici, Saurabh Singh, Sung Jin Hwang, Michele Covell
mathjax: true
---

* content
{:toc}

##### Abstract
The leading approach for image compression with artificial neural networks (ANNs) is to learn a nonlinear transform and a fixed entropy model that are optimized for rate-distortion performance. We show that this approach can be significantly improved by incorporating spatially local, image-dependent entropy models. The key insight is that existing ANN-based methods learn an entropy model that is shared between the encoder and decoder, but they do not transmit any side information that would allow the model to adapt to the structure of a specific image. We present a method for augmenting ANN-based image coders with image-dependent side information that leads to a 17.8% rate reduction over a state-of-the-art ANN-based baseline model on a standard evaluation set, and 70-98% reductions on images with low visual complexity that are poorly captured by a fixed, global entropy model.

##### Abstract (translated by Google)
用人工神经网络（ANN）进行图像压缩的主要方法是学习非线性变换和固定熵模型，这些模型针对速率失真性能进行了优化。我们表明，这种方法可以通过结合空间局部的，图像相关的熵模型来显着改善。关键的见解是，现有的基于ANN的方法学习了编码器和解码器之间共享的熵模型，但是它们不传输任何允许模型适应特定图像结构的边信息。我们提出了一种基于图像相关副信息的基于ANN的图像编码器的增强方法，其导致在标准评估集上基于最先进的基于ANN的基线模型降低17.8％的速率，并且70-98％降低视觉复杂度低的图像，而这些图像由固定的全局熵模型难以捕获。

##### URL
[http://arxiv.org/abs/1805.12295](http://arxiv.org/abs/1805.12295)

##### PDF
[http://arxiv.org/pdf/1805.12295](http://arxiv.org/pdf/1805.12295)

