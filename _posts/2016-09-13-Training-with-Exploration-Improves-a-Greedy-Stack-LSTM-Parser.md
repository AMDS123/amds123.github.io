---
layout: post
title: "Training with Exploration Improves a Greedy Stack-LSTM Parser"
date: 2016-09-13 14:54:51
categories: arXiv_SD
tags: arXiv_SD RNN Prediction
author: Miguel Ballesteros, Yoav Goldberg, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We adapt the greedy Stack-LSTM dependency parser of Dyer et al. (2015) to support a training-with-exploration procedure using dynamic oracles(Goldberg and Nivre, 2013) instead of cross-entropy minimization. This form of training, which accounts for model predictions at training time rather than assuming an error-free action history, improves parsing accuracies for both English and Chinese, obtaining very strong results for both languages. We discuss some modifications needed in order to get training with exploration to work well for a probabilistic neural-network.

##### Abstract (translated by Google)
我们调整了Dyer等人的贪婪Stack-LSTM依赖分析器。 （2015）支持使用动态神谕（Goldberg和Nivre，2013）的训练与探索程序，而不是交叉熵最小化。这种训练形式的训练时间，而不是假设一个没有错误的行动历史记录模型预测，提高了英文和中文的解析准确性，获得非常强烈的结果，这两种语言。我们讨论一些需要的修改，以便通过探索训练，使其适合于概率神经网络。

##### URL
[https://arxiv.org/abs/1603.03793](https://arxiv.org/abs/1603.03793)

##### PDF
[https://arxiv.org/pdf/1603.03793](https://arxiv.org/pdf/1603.03793)

