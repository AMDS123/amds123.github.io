---
layout: post
title: "Variational Deep Embedding: An Unsupervised and Generative Approach to Clustering"
date: 2017-06-28 02:45:32
categories: arXiv_CV
tags: arXiv_CV Embedding Inference Quantitative
author: Zhuxi Jiang, Yin Zheng, Huachun Tan, Bangsheng Tang, Hanning Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering is among the most fundamental tasks in computer vision and machine learning. In this paper, we propose Variational Deep Embedding (VaDE), a novel unsupervised generative clustering approach within the framework of Variational Auto-Encoder (VAE). Specifically, VaDE models the data generative procedure with a Gaussian Mixture Model (GMM) and a deep neural network (DNN): 1) the GMM picks a cluster; 2) from which a latent embedding is generated; 3) then the DNN decodes the latent embedding into observables. Inference in VaDE is done in a variational way: a different DNN is used to encode observables to latent embeddings, so that the evidence lower bound (ELBO) can be optimized using Stochastic Gradient Variational Bayes (SGVB) estimator and the reparameterization trick. Quantitative comparisons with strong baselines are included in this paper, and experimental results show that VaDE significantly outperforms the state-of-the-art clustering methods on 4 benchmarks from various modalities. Moreover, by VaDE's generative nature, we show its capability of generating highly realistic samples for any specified cluster, without using supervised information during training. Lastly, VaDE is a flexible and extensible framework for unsupervised generative clustering, more general mixture models than GMM can be easily plugged in.

##### Abstract (translated by Google)
聚类是计算机视觉和机器学习中最基本的任务之一。在本文中，我们提出了变分深度嵌入（VaDE），一种在变分自动编码器（VAE）框架内的新型无监督生成聚类方法。具体来说，VaDE用高斯混合模型（GMM）和深度神经网络（DNN）对数据生成过程进行建模：1）GMM挑选一个簇; 2）从中产生潜在的嵌入; 3）然后DNN将潜在的嵌入解码成可观测量。 VaDE中的推理是以变分方式完成的：使用不同的DNN来将可观测量编码为潜在嵌入，从而使用随机梯度变分贝叶斯（SGVB）估计器和重新参数化技巧来优化证据下界（ELBO）。本文包括了具有强基线的定量比较，实验结果表明，VaDE显着优于各种形式的4个基准的最先进的聚类方法。而且，通过VaDE的生成性，我们展示了它能够为任何指定的聚类生成高度真实的样本，而不需要在训练过程中使用监督信息。最后，VaDE是无监督生成聚类的灵活和可扩展的框架，比GMM更容易插入更一般的混合模型。

##### URL
[https://arxiv.org/abs/1611.05148](https://arxiv.org/abs/1611.05148)

##### PDF
[https://arxiv.org/pdf/1611.05148](https://arxiv.org/pdf/1611.05148)

