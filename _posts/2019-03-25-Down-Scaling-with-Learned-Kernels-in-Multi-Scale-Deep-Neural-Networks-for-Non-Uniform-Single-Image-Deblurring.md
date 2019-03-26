---
layout: post
title: "Down-Scaling with Learned Kernels in Multi-Scale Deep Neural Networks for Non-Uniform Single Image Deblurring"
date: 2019-03-25 07:23:07
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Dongwon Park, Jisoo Kim, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-scale approach has been used for blind image / video deblurring problems to yield excellent performance for both conventional and recent deep-learning-based state-of-the-art methods. Bicubic down-sampling is a typical choice for multi-scale approach to reduce spatial dimension after filtering with a fixed kernel. However, this fixed kernel may be sub-optimal since it may destroy important information for reliable deblurring such as strong edges. We propose convolutional neural network (CNN)-based down-scale methods for multi-scale deep-learning-based non-uniform single image deblurring. We argue that our CNN-based down-scaling effectively reduces the spatial dimension of the original image, while learned kernels with multiple channels may well-preserve necessary details for deblurring tasks. For each scale, we adopt to use RCAN (Residual Channel Attention Networks) as a backbone network to further improve performance. Our proposed method yielded state-of-the-art performance on GoPro dataset by large margin. Our proposed method was able to achieve 2.59dB higher PSNR than the current state-of-the-art method by Tao. Our proposed CNN-based down-scaling was the key factor for this excellent performance since the performance of our network without it was decreased by 1.98dB. The same networks trained with GoPro set were also evaluated on large-scale Su dataset and our proposed method yielded 1.15dB better PSNR than the Tao's method. Qualitative comparisons on Lai dataset also confirmed the superior performance of our proposed method over other state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10157](http://arxiv.org/abs/1903.10157)

##### PDF
[http://arxiv.org/pdf/1903.10157](http://arxiv.org/pdf/1903.10157)

