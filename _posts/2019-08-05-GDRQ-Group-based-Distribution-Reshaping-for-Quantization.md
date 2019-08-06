---
layout: post
title: "GDRQ: Group-based Distribution Reshaping for Quantization"
date: 2019-08-05 05:44:52
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Inference Classification Detection
author: Haibao Yu, Tuopu Wen, Guangliang Cheng, Jiankai Sun, Qi Han, Jianping Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Low-bit quantization is challenging to maintain high performance with limited model capacity (e.g., 4-bit for both weights and activations). Naturally, the distribution of both weights and activations in deep neural network are Gaussian-like. Nevertheless, due to the limited bitwidth of low-bit model, uniform-like distributed weights and activations have been proved to be more friendly to quantization while preserving accuracy~\cite{Han2015Learning}. Motivated by this, we propose Scale-Clip, a Distribution Reshaping technique that can reshape weights or activations into a uniform-like distribution in a dynamic manner. Furthermore, to increase the model capability for a low-bit model, a novel Group-based Quantization algorithm is proposed to split the filters into several groups. Different groups can learn different quantization parameters, which can be elegantly merged in to batch normalization layer without extra computational cost in the inference stage. Finally, we integrate Scale-Clip technique with Group-based Quantization algorithm and propose the Group-based Distribution Reshaping Quantization (GDQR) framework to further improve the quantization performance. Experiments on various networks (e.g. VGGNet and ResNet) and vision tasks (e.g. classification, detection and segmentation) demonstrate that our framework achieves good performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01477](http://arxiv.org/abs/1908.01477)

##### PDF
[http://arxiv.org/pdf/1908.01477](http://arxiv.org/pdf/1908.01477)

