---
layout: post
title: "Natural-Parameter Networks: A Class of Probabilistic Neural Networks"
date: 2016-11-02 02:32:05
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Hao Wang, Xingjian Shi, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks (NN) have achieved state-of-the-art performance in various applications. Unfortunately in applications where training data is insufficient, they are often prone to overfitting. One effective way to alleviate this problem is to exploit the Bayesian approach by using Bayesian neural networks (BNN). Another shortcoming of NN is the lack of flexibility to customize different distributions for the weights and neurons according to the data, as is often done in probabilistic graphical models. To address these problems, we propose a class of probabilistic neural networks, dubbed natural-parameter networks (NPN), as a novel and lightweight Bayesian treatment of NN. NPN allows the usage of arbitrary exponential-family distributions to model the weights and neurons. Different from traditional NN and BNN, NPN takes distributions as input and goes through layers of transformation before producing distributions to match the target output distributions. As a Bayesian treatment, efficient backpropagation (BP) is performed to learn the natural parameters for the distributions over both the weights and neurons. The output distributions of each layer, as byproducts, may be used as second-order representations for the associated tasks such as link prediction. Experiments on real-world datasets show that NPN can achieve state-of-the-art performance.

##### Abstract (translated by Google)
神经网络（NN）已经在各种应用中实现了最先进的性能。不幸的是，在培训数据不足的应用中，他们往往容易出现过度配合。贝叶斯神经网络（BNN）利用贝叶斯方法来解决这个问题是一种有效的方法。神经网络的另一个缺点是缺乏灵活性来根据数据定制权重和神经元的不同分布，就像在概率图形模型中经常做的那样。为了解决这些问题，我们提出了一类被称为自然参数网络（NPN）的概率神经网络作为神经网络的新颖和轻量级贝叶斯处理。 NPN允许使用任意的指数族分布来建模权重和神经元。不同于传统的NN和BNN，NPN以分布为输入，经过层层转化，产生分布以匹配目标产出分布。作为贝叶斯治疗，执行有效的反向传播（BP）以学习在权重和神经元上的分布的自然参数。作为副产品的每层的输出分布可以用作关联任务的二阶表示，例如链接预测。在现实世界的数据集上的实验表明，NPN可以达到最先进的性能。

##### URL
[https://arxiv.org/abs/1611.00448](https://arxiv.org/abs/1611.00448)

##### PDF
[https://arxiv.org/pdf/1611.00448](https://arxiv.org/pdf/1611.00448)

