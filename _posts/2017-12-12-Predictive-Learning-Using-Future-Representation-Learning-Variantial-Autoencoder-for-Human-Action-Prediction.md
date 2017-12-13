---
layout: post
title: "Predictive Learning: Using Future Representation Learning Variantial Autoencoder for Human Action Prediction"
date: 2017-12-12 11:22:18
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Represenation_Learning Prediction Recognition
author: Yu Runsheng, Shi Zhenyu, Ma Qiongxiong, Qing Laiyun
mathjax: true
---

* content
{:toc}

##### Abstract
The unsupervised Pretraining method has been widely used in aiding human action recognition. However, existing methods focus on reconstructing the already present frames rather than generating frames which happen in future.In this paper, We propose an improved Variantial Autoencoder model to extract the features with a high connection to the coming scenarios, also known as Predictive Learning. Our framework lists as following: two steam 3D-convolution neural networks are used to extract both spatial and temporal information as latent variables. Then a resample method is introduced to create new normal distribution probabilistic latent variables and finally, the deconvolution neural network will use these latent variables generate next frames. Through this possess, we train the model to focus more on how to generate the future and thus it will extract the future high connected features. In the experiment stage, A large number of experiments on UT and UCF101 datasets reveal that future generation aids Prediction does improve the performance. Moreover, the Future Representation Learning Network reach a higher score than other methods when in half observation. This means that Future Representation Learning is better than the traditional Representation Learning and other state- of-the-art methods in solving the human action prediction problems to some extends.

##### Abstract (translated by Google)
无监督Pretraining方法已被广泛用于帮助人类行为识别。然而，现有方法的重点在于重构已经存在的帧，而不是生成将来发生的帧。本文提出了一种改进的Variantial Autoencoder模型来提取与未来情景高度相关的特征，也称为预测学习。我们的框架列出如下：两个蒸汽3D卷积神经网络被用来提取空间和时间信息作为潜在变量。然后引入重采样方法创建新的正态分布概率潜变量，最后由去卷积神经网络利用这些潜变量产生下一帧。通过这种拥有，我们训练模型更多地关注如何生成未来，从而提取未来的高连通性特征。在实验阶段，对UT和UCF101数据集进行的大量实验揭示，未来一代辅助预测确实提高了性能。此外，未来代表学习网络在半观察中比其他方法得分更高。这就意味着未来的表征学习在解决人类行为预测问题方面，比传统的表征学习和其他一些先进的方法要好一些。

##### URL
[http://arxiv.org/abs/1711.09265](http://arxiv.org/abs/1711.09265)

##### PDF
[http://arxiv.org/pdf/1711.09265](http://arxiv.org/pdf/1711.09265)

