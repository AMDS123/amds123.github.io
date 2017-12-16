---
layout: post
title: "Deep Learning from Noisy Image Labels with Quality Embedding"
date: 2017-11-02 01:19:25
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Deep_Learning Prediction Recognition
author: Jiangchao Yao, Jiajie Wang, Ivor Tsang, Ya Zhang, Jun Sun, Chengqi Zhang, Rui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
There is an emerging trend to leverage noisy image datasets in many visual recognition tasks. However, the label noise among the datasets severely degenerates the \mbox{performance of deep} learning approaches. Recently, one mainstream is to introduce the latent label to handle label noise, which has shown promising improvement in the network designs. Nevertheless, the mismatch between latent labels and noisy labels still affects the predictions in such methods. To address this issue, we propose a quality embedding model, which explicitly introduces a quality variable to represent the trustworthiness of noisy labels. Our key idea is to identify the mismatch between the latent and noisy labels by embedding the quality variables into different subspaces, which effectively minimizes the noise effect. At the same time, the high-quality labels is still able to be applied for training. To instantiate the model, we further propose a Contrastive-Additive Noise network (CAN), which consists of two important layers: (1) the contrastive layer estimates the quality variable in the embedding space to reduce noise effect; and (2) the additive layer aggregates the prior predictions and noisy labels as the posterior to train the classifier. Moreover, to tackle the optimization difficulty, we deduce an SGD algorithm with the reparameterization tricks, which makes our method scalable to big data. We conduct the experimental evaluation of the proposed method over a range of noisy image datasets. Comprehensive results have demonstrated CAN outperforms the state-of-the-art deep learning approaches.

##### Abstract (translated by Google)
在许多视觉识别任务中利用噪声图像数据集有一个新兴的趋势。然而，数据集之间的标签噪声严重退化了深度学习方法的性能。最近，一个主流是引入潜在的标签来处理标签噪声，这在网络设计上已经有了很大的改进。尽管如此，潜在标签和嘈杂标签之间的不匹配仍然会影响这种方法的预测。为了解决这个问题，我们提出了一个质量嵌入模型，它明确引入了一个质量变量来表示噪声标签的可信度。我们的主要思想是通过将质量变量嵌入到不同的子空间中来识别潜在标签和噪声标签之间的不匹配，从而有效地将噪声影响降至最低。同时，高质量的标签仍然可以申请培训。为了实例化模型，我们进一步提出了一个对比加性噪声网络（CAN），它由两个重要层组成：（1）对比层估计嵌入空间中的质量变量以减少噪声影响; （2）加性层将先验预测和噪声标签聚合为训练分类器的后验。此外，为了解决优化难题，我们推导出一种具有重新参数化技巧的SGD算法，这使得我们的方法可以扩展到大数据。我们在一系列噪声图像数据集上对所提出的方法进行了实验评估。综合结果显示，CAN能够胜过最先进的深度学习方法。

##### URL
[https://arxiv.org/abs/1711.00583](https://arxiv.org/abs/1711.00583)

##### PDF
[https://arxiv.org/pdf/1711.00583](https://arxiv.org/pdf/1711.00583)

