---
layout: post
title: "Dynamic Prediction Length for Time Series with Sequence to Sequence Networks"
date: 2018-07-02 01:00:23
categories: arXiv_AI
tags: arXiv_AI Inference RNN Prediction
author: Mark Harmon, Diego Klabjan
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks and sequence to sequence models require a predetermined length for prediction output length. Our model addresses this by allowing the network to predict a variable length output in inference. A new loss function with a tailored gradient computation is developed that trades off prediction accuracy and output length. The model utilizes a function to determine whether a particular output at a time should be evaluated or not given a predetermined threshold. We evaluate the model on the problem of predicting the prices of securities. We find that the model makes longer predictions for more stable securities and it naturally balances prediction accuracy and length.

##### Abstract (translated by Google)
递归神经网络和序列到序列模型需要预定长度用于预测输出长度。我们的模型通过允许网络在推理中预测可变长度输出来解决这个问题。开发了具有定制梯度计算的新损失函数，其折衷预测精度和输出长度。该模型利用函数来确定是否应评估一次特定输出或不给定预定阈值。我们评估了预测证券价格问题的模型。我们发现该模型对更稳定的证券做出更长的预测，并且自然地平衡了预测的准确性和长度。

##### URL
[http://arxiv.org/abs/1807.00425](http://arxiv.org/abs/1807.00425)

##### PDF
[http://arxiv.org/pdf/1807.00425](http://arxiv.org/pdf/1807.00425)

