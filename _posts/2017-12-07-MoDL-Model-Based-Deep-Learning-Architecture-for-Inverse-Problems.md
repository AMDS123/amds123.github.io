---
layout: post
title: "MoDL: Model Based Deep Learning Architecture for Inverse Problems"
date: 2017-12-07 21:13:13
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Deep_Learning
author: Hemant Kumar Aggarwal, Merry P. Mani, Mathews Jacob
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a model-based image reconstruction framework with a convolution neural network (CNN) based regularization prior. While CNN based image recovery methods are ideally suited for inverse problems with a convolutional structure, deep learning architectures for problems that do not have a convolutional structure (e.g., parallel MRI, structured illumination microscopy) are less obvious. The proposed formulation provides a systematic approach for deriving deep architectures for inverse problems with the arbitrary structure. Since the forward model is explicitly accounted for, a much smaller network with fewer parameters is sufficient to capture the image information. In addition, this strategy enables the re-use of the learned network in acquisition schemes with slightly different parameter settings (e.g., different image size, undersampling patterns) and allows one to account for the imperfections of the acquisition scheme. The main difference of the framework from existing model based schemes is the sharing of the network weights across iterations and channels, which provides benefits including considerably lower demand for training data, reduced risk of overfitting, and reconstruction algorithms with significantly reduced memory footprint.

##### Abstract (translated by Google)
我们引入基于模型的图像重建框架，其中基于卷积神经网络（CNN）的正则化优先。尽管基于CNN的图像恢复方法理想地适合于具有卷积结构的逆问题，但是针对不具有卷积结构（例如，平行MRI，结构化照明显微镜）的问题的深度学习体系结构不太明显。拟议的公式提供了一个系统的方法来推导任意结构反演问题的深层架构。由于正向模型是明确说明的，具有较少参数的小得多的网络足以捕捉图像信息。此外，该策略使得能够在具有略微不同的参数设置（例如，不同的图像大小，欠采样模式）的采集方案中重新使用所学习的网络，并且允许考虑采集方案的不完善性。与现有的基于模型的方案的主要区别在于跨越迭代和信道的网络权重共享，这提供了包括相当低的对训练数据的需求，降低的过度拟合风险以及具有显着减少的存储器占用空间的重建算法的益处。

##### URL
[http://arxiv.org/abs/1712.02862](http://arxiv.org/abs/1712.02862)

##### PDF
[http://arxiv.org/pdf/1712.02862](http://arxiv.org/pdf/1712.02862)

