---
layout: post
title: "Diversity encouraged learning of unsupervised LSTM ensemble for neural activity video prediction"
date: 2018-07-03 02:39:38
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Yilin Song, Jonathan Viventi, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Being able to predict the neural signal in the near future from the current and previous observations has the potential to enable real-time responsive brain stimulation to suppress seizures. We have investigated how to use an auto-encoder model consisting of LSTM cells for such prediction. Recog- nizing that there exist multiple activity pattern clusters, we have further explored to train an ensemble of LSTM mod- els so that each model can specialize in modeling certain neural activities, without explicitly clustering the training data. We train the ensemble using an ensemble-awareness loss, which jointly solves the model assignment problem and the error minimization problem. During training, for each training sequence, only the model that has the lowest recon- struction and prediction error is updated. Intrinsically such a loss function enables each LTSM model to be adapted to a subset of the training sequences that share similar dynamic behavior. We demonstrate this can be trained in an end- to-end manner and achieve significant accuracy in neural activity prediction.

##### Abstract (translated by Google)
能够从当前和先前的观察预测近期的神经信号有可能实现实时响应性脑刺激以抑制癫痫发作。我们已经研究了如何使用由LSTM单元组成的自动编码器模型来进行这种预测。通过认识到存在多个活动模式聚类，我们进一步探索了训练LSTM模型的集合，以便每个模型都可以专门建模某些神经活动，而无需明确地聚类训练数据。我们使用集合意识损失来训练集合，它共同解决了模型分配问题和误差最小化问题。在训练期间，对于每个训练序列，仅更新具有最低重构和预测误差的模型。本质上，这种损失函数使得每个LTSM模型能够适应共享相似动态行为的训练序列的子集。我们证明这可以以端到端的方式进行训练，并在神经活动预测中实现显着的准确性。

##### URL
[http://arxiv.org/abs/1611.04899](http://arxiv.org/abs/1611.04899)

##### PDF
[http://arxiv.org/pdf/1611.04899](http://arxiv.org/pdf/1611.04899)

