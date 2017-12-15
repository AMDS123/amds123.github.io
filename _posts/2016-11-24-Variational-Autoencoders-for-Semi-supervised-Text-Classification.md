---
layout: post
title: "Variational Autoencoders for Semi-supervised Text Classification"
date: 2016-11-24 08:18:31
categories: arXiv_SD
tags: arXiv_SD Review Text_Classification Reinforcement_Learning Image_Classification Optimization RNN Classification
author: Weidi Xu, Haoze Sun, Chao Deng, Ying Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Although semi-supervised variational autoencoder (SemiVAE) works in image classification task, it fails in text classification task if using vanilla LSTM as its decoder. From a perspective of reinforcement learning, it is verified that the decoder's capability to distinguish between different categorical labels is essential. Therefore, Semi-supervised Sequential Variational Autoencoder (SSVAE) is proposed, which increases the capability by feeding label into its decoder RNN at each time-step. Two specific decoder structures are investigated and both of them are verified to be effective. Besides, in order to reduce the computational complexity in training, a novel optimization method is proposed, which estimates the gradient of the unlabeled objective function by sampling, along with two variance reduction techniques. Experimental results on Large Movie Review Dataset (IMDB) and AG's News corpus show that the proposed approach significantly improves the classification accuracy compared with pure-supervised classifiers, and achieves competitive performance against previous advanced methods. State-of-the-art results can be obtained by integrating other pretraining-based methods.

##### Abstract (translated by Google)
尽管半监督变分自动编码器（SemiVAE）在图像分类任务中起作用，但如果使用香草LSTM作为其解码器，则在文本分类任务中失败。从强化学习的角度来看，验证了解码器区分不同分类标签的能力是必不可少的。因此，提出了半监督的顺序变分自动编码器（SSVAE），通过在每个时间步将标签送入解码器的RNN来提高能力。两个具体的解码器结构进行了调查，他们都证实是有效的。此外，为了降低训练的计算复杂度，提出了一种新的优化方法，通过抽样估计未标记目标函数的梯度，并结合两种方差约简技术。大型电影评论数据集（IMDB）和AG新闻语料库的实验结果表明，与纯监督分类器相比，该方法显着提高了分类精度，并且与以前的高级方法相比具有竞争性。最新的结果可以通过整合其他基于训练的方法来获得。

##### URL
[https://arxiv.org/abs/1603.02514](https://arxiv.org/abs/1603.02514)

##### PDF
[https://arxiv.org/pdf/1603.02514](https://arxiv.org/pdf/1603.02514)

