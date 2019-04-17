---
layout: post
title: "Feature Distillation: DNN-Oriented JPEG Compression Against Adversarial Examples"
date: 2019-04-16 16:46:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Zihao Liu, Qi Liu, Tao Liu, Nuo Xu, Xue Lin, Yanzhi Wang, Wujie Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Image compression-based approaches for defending against the adversarial-example attacks, which threaten the safety use of deep neural networks (DNN), have been investigated recently. However, prior works mainly rely on directly tuning parameters like compression rate, to blindly reduce image features, thereby lacking guarantee on both defense efficiency (i.e. accuracy of polluted images) and classification accuracy of benign images, after applying defense methods. To overcome these limitations, we propose a JPEG-based defensive compression framework, namely "feature distillation", to effectively rectify adversarial examples without impacting classification accuracy on benign data. Our framework significantly escalates the defense efficiency with marginal accuracy reduction using a two-step method: First, we maximize malicious features filtering of adversarial input perturbations by developing defensive quantization in frequency domain of JPEG compression or decompression, guided by a semi-analytical method; Second, we suppress the distortions of benign features to restore classification accuracy through a DNN-oriented quantization refine process. Our experimental results show that proposed "feature distillation" can significantly surpass the latest input-transformation based mitigations such as Quilting and TV Minimization in three aspects, including defense efficiency (improve classification accuracy from $\sim20\%$ to $\sim90\%$ on adversarial examples), accuracy of benign images after defense ($\le1\%$ accuracy degradation), and processing time per image ($\sim259\times$ Speedup). Moreover, our solution can also provide the best defense efficiency ($\sim60\%$ accuracy) against the recent adaptive attack with least accuracy reduction ($\sim1\%$) on benign images when compared with other input-transformation based defense methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.05787](http://arxiv.org/abs/1803.05787)

##### PDF
[http://arxiv.org/pdf/1803.05787](http://arxiv.org/pdf/1803.05787)

