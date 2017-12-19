---
layout: post
title: "Deep Gaussian Conditional Random Field Network: A Model-based Deep Network for Discriminative Denoising"
date: 2015-11-12 20:49:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Raviteja Vemulapalli, Oncel Tuzel, Ming-Yu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep network architecture for image\\ denoising based on a Gaussian Conditional Random Field (GCRF) model. In contrast to the existing discriminative denoising methods that train a separate model for each noise level, the proposed deep network explicitly models the input noise variance and hence is capable of handling a range of noise levels. Our deep network, which we refer to as deep GCRF network, consists of two sub-networks: (i) a parameter generation network that generates the pairwise potential parameters based on the noisy input image, and (ii) an inference network whose layers perform the computations involved in an iterative GCRF inference procedure.\ We train the entire deep GCRF network (both parameter generation and inference networks) discriminatively in an end-to-end fashion by maximizing the peak signal-to-noise ratio measure. Experiments on Berkeley segmentation and PASCALVOC datasets show that the proposed deep GCRF network outperforms state-of-the-art image denoising approaches for several noise levels.

##### Abstract (translated by Google)
我们提出了一种基于高斯条件随机场（GCRF）模型的图像去噪新型深度网络结构。与现有的针对每个噪声水平训练单独模型的区别性去噪方法相反，所提出的深度网络明确地模拟了输入噪声方差，因此能够处理一定范围的噪声水平。我们称之为深度GCRF网络的深层网络由两个子网络组成：（i）一个参数生成网络，它根据有噪声的输入图像生成成对的潜在参数;（ii）一个推理网络，迭代GCRF推理过程中所涉及的计算。我们通过最大化峰值信噪比测量来以端对端的方式有区别地训练整个深度GCRF网络（参数生成和推理网络）。伯克利分割和PASCALVOC数据集的实验表明，所提出的深GCRF网络胜过了用于多个噪声级别的最先进的图像去噪方法。

##### URL
[https://arxiv.org/abs/1511.04067](https://arxiv.org/abs/1511.04067)

##### PDF
[https://arxiv.org/pdf/1511.04067](https://arxiv.org/pdf/1511.04067)

