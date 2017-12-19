---
layout: post
title: "A Deep Generative Deconvolutional Image Model"
date: 2015-12-23 03:10:29
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Yunchen Pu, Xin Yuan, Andrew Stevens, Chunyuan Li, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
A deep generative model is developed for representation and analysis of images, based on a hierarchical convolutional dictionary-learning framework. Stochastic {\em unpooling} is employed to link consecutive layers in the model, yielding top-down image generation. A Bayesian support vector machine is linked to the top-layer features, yielding max-margin discrimination. Deep deconvolutional inference is employed when testing, to infer the latent features, and the top-layer features are connected with the max-margin classifier for discrimination tasks. The model is efficiently trained using a Monte Carlo expectation-maximization (MCEM) algorithm, with implementation on graphical processor units (GPUs) for efficient large-scale learning, and fast testing. Excellent results are obtained on several benchmark datasets, including ImageNet, demonstrating that the proposed model achieves results that are highly competitive with similarly sized convolutional neural networks.

##### Abstract (translated by Google)
基于层次卷积字典学习框架，开发了一个深度生成模型来表示和分析图像。随机{\ em unpooling}被用来连接模型中的连续层，产生自上而下的图像生成。贝叶斯支持向量机被链接到顶层特征，产生最大边缘区分。深度解卷积推理在测试时被采用，以推断潜在特征，并且顶层特征与用于区分任务的最大边缘分类器连接。该模型使用蒙特卡罗期望最大化（MCEM）算法进行高效训练，在图形处理器单元（GPU）上实现，以进行高效的大规模学习和快速测试。在包括ImageNet的几个基准数据集上获得了优异的结果，表明所提出的模型实现了与相似大小的卷积神经网络高度竞争的结果。

##### URL
[https://arxiv.org/abs/1512.07344](https://arxiv.org/abs/1512.07344)

##### PDF
[https://arxiv.org/pdf/1512.07344](https://arxiv.org/pdf/1512.07344)

