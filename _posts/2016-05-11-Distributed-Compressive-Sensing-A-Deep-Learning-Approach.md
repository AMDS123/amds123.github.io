---
layout: post
title: "Distributed Compressive Sensing: A Deep Learning Approach"
date: 2016-05-11 22:18:13
categories: arXiv_CV
tags: arXiv_CV Sparse RNN Deep_Learning
author: Hamid Palangi, Rabab Ward, Li Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Various studies that address the compressed sensing problem with Multiple Measurement Vectors (MMVs) have been recently carried. These studies assume the vectors of the different channels to be jointly sparse. In this paper, we relax this condition. Instead we assume that these sparse vectors depend on each other but that this dependency is unknown. We capture this dependency by computing the conditional probability of each entry in each vector being non-zero, given the "residuals" of all previous vectors. To estimate these probabilities, we propose the use of the Long Short-Term Memory (LSTM)[1], a data driven model for sequence modelling that is deep in time. To calculate the model parameters, we minimize a cross entropy cost function. To reconstruct the sparse vectors at the decoder, we propose a greedy solver that uses the above model to estimate the conditional probabilities. By performing extensive experiments on two real world datasets, we show that the proposed method significantly outperforms the general MMV solver (the Simultaneous Orthogonal Matching Pursuit (SOMP)) and a number of the model-based Bayesian methods. The proposed method does not add any complexity to the general compressive sensing encoder. The trained model is used just at the decoder. As the proposed method is a data driven method, it is only applicable when training data is available. In many applications however, training data is indeed available, e.g. in recorded images and videos.

##### Abstract (translated by Google)
最近进行了各种研究，解决多测量向量（MMV）压缩感测问题。这些研究假设不同渠道的媒介共同稀疏。在这篇文章中，我们放松了这个条件。相反，我们假设这些稀疏矢量依赖于彼此，但是这个依赖是未知的。我们通过计算每个向量中的每个条目的条件概率非零来捕获这种依赖性，给定所有先前向量的“残差”。为了估计这些概率，我们建议使用长时间短期记忆（LSTM）[1]，这是一个数据驱动的时间序列模型。为了计算模型参数，我们最小化交叉熵成本函数。为了在解码器处重建稀疏向量，我们提出了一个贪心求解器，它使用上述模型来估计条件概率。通过在两个真实世界的数据集上进行大量的实验，我们证明了所提出的方法明显优于一般MMV求解器（同时正交匹配追踪（SOMP））和一些基于模型的贝叶斯方法。所提出的方法不会给一般的压缩感测编码器增加任何复杂性。训练好的模型只用在解码器上。由于所提出的方法是一种数据驱动的方法，只有在训练数据可用时才适用。然而，在许多应用中，训练数据确实是可用的，例如，在录制的图像和视频。

##### URL
[https://arxiv.org/abs/1508.04924](https://arxiv.org/abs/1508.04924)

##### PDF
[https://arxiv.org/pdf/1508.04924](https://arxiv.org/pdf/1508.04924)

