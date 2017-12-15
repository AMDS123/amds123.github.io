---
layout: post
title: "GMM-Free Flat Start Sequence-Discriminative DNN Training"
date: 2016-10-11 09:52:57
categories: arXiv_CL
tags: arXiv_CL
author: Gábor Gosztolya, Tamás Grósz, László Tóth
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, attempts have been made to remove Gaussian mixture models (GMM) from the training process of deep neural network-based hidden Markov models (HMM/DNN). For the GMM-free training of a HMM/DNN hybrid we have to solve two problems, namely the initial alignment of the frame-level state labels and the creation of context-dependent states. Although flat-start training via iteratively realigning and retraining the DNN using a frame-level error function is viable, it is quite cumbersome. Here, we propose to use a sequence-discriminative training criterion for flat start. While sequence-discriminative training is routinely applied only in the final phase of model training, we show that with proper caution it is also suitable for getting an alignment of context-independent DNN models. For the construction of tied states we apply a recently proposed KL-divergence-based state clustering method, hence our whole training process is GMM-free. In the experimental evaluation we found that the sequence-discriminative flat start training method is not only significantly faster than the straightforward approach of iterative retraining and realignment, but the word error rates attained are slightly better as well.

##### Abstract (translated by Google)
最近，已经尝试从基于深度神经网络的隐马尔可夫模型（HMM / DNN）的训练过程中去除高斯混合模型（GMM）。对于HMM / DNN混合的无GMM训练，我们必须解决两个问题，即帧级状态标签的初始对齐和创建依赖于上下文的状态。尽管通过使用帧级错误函数迭代地重新调整和再训练DNN的平坦启动训练是可行的，但是这是非常麻烦的。在这里，我们建议使用序列判别式训练标准来进行平坦启动。虽然序列识别训练通常只应用于模型训练的最后阶段，但是我们还应该小心谨慎地使用它，也适合于获得与上下文无关的DNN模型的对齐。对于绑定状态的构造，我们应用了最近提出的基于KL散度的状态聚类方法，因此我们的整个训练过程是无GMM的。在实验评估中，我们发现序列判别平坦启动训练方法不仅明显快于迭代再训练和重排的直接方法，而且所获得的误字率也稍好一些。

##### URL
[https://arxiv.org/abs/1610.03256](https://arxiv.org/abs/1610.03256)

##### PDF
[https://arxiv.org/pdf/1610.03256](https://arxiv.org/pdf/1610.03256)

