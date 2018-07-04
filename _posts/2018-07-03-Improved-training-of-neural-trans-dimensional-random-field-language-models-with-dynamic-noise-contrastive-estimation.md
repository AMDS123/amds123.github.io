---
layout: post
title: "Improved training of neural trans-dimensional random field language models with dynamic noise-contrastive estimation"
date: 2018-07-03 06:36:48
categories: arXiv_CL
tags: arXiv_CL Sparse RNN Language_Model
author: Bin Wang, Zhijian Ou
mathjax: true
---

* content
{:toc}

##### Abstract
A new whole-sentence language model - neural trans-dimensional random field language model (neural TRF LM), where sentences are modeled as a collection of random fields, and the potential function is defined by a neural network, has been introduced and successfully trained by noise-contrastive estimation (NCE). In this paper, we extend NCE and propose dynamic noise-contrastive estimation (DNCE) to solve the two problems observed in NCE training. First, a dynamic noise distribution is introduced and trained simultaneously to converge to the data distribution. This helps to significantly cut down the noise sample number used in NCE and reduce the training cost. Second, DNCE discriminates between sentences generated from the noise distribution and sentences generated from the interpolation of the data distribution and the noise distribution. This alleviates the overfitting problem caused by the sparseness of the training set. With DNCE, we can successfully and efficiently train neural TRF LMs on large corpus (about 0.8 billion words) with large vocabulary (about 568 K words). Neural TRF LMs perform as good as LSTM LMs with less parameters and being 5x~114x faster in rescoring sentences. Interpolating neural TRF LMs with LSTM LMs and n-gram LMs can further reduce the error rates.

##### Abstract (translated by Google)
一种新的全句语言模型 - 神经跨维随机场语言模型（神经TRF LM），其中句子被建模为随机场的集合，并且潜在的功能由神经网络定义，已被引入并成功训练通过噪声对比估计（NCE）。在本文中，我们扩展NCE并提出动态噪声对比估计（DNCE）来解决在NCE训练中观察到的两个问题。首先，引入动态噪声分布并同时训练以收敛到数据分布。这有助于显着减少NCE中使用的噪声样本数量并降低培训成本。其次，DNCE区分由噪声分布产生的句子和由数据分布的插值和噪声分布产生的句子。这减轻了由训练集的稀疏性引起的过度拟合问题。通过DNCE，我们可以成功地和有效地训练大型语料库（约8亿字）的神经TRF LMs，具有大词汇量（约568 K字）。神经TRF LM的表现与LSTM LMs一样好，参数较少，并且在重新判断句子时速度提高5倍~114倍。使用LSTM LM和n-gram LM插值神经TRF LM可以进一步降低错误率。

##### URL
[https://arxiv.org/abs/1807.00993](https://arxiv.org/abs/1807.00993)

##### PDF
[https://arxiv.org/pdf/1807.00993](https://arxiv.org/pdf/1807.00993)

