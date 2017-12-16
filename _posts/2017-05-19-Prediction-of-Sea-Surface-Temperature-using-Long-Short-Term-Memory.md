---
layout: post
title: "Prediction of Sea Surface Temperature using Long Short-Term Memory"
date: 2017-05-19 05:14:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Face RNN Prediction Relation
author: Qin Zhang, Hui Wang, Junyu Dong, Guoqiang Zhong, Xin Sun
mathjax: true
---

* content
{:toc}

##### Abstract
This letter adopts long short-term memory(LSTM) to predict sea surface temperature(SST), which is the first attempt, to our knowledge, to use recurrent neural network to solve the problem of SST prediction, and to make one week and one month daily prediction. We formulate the SST prediction problem as a time series regression problem. LSTM is a special kind of recurrent neural network, which introduces gate mechanism into vanilla RNN to prevent the vanished or exploding gradient problem. It has strong ability to model the temporal relationship of time series data and can handle the long-term dependency problem well. The proposed network architecture is composed of two kinds of layers: LSTM layer and full-connected dense layer. LSTM layer is utilized to model the time series relationship. Full-connected layer is utilized to map the output of LSTM layer to a final prediction. We explore the optimal setting of this architecture by experiments and report the accuracy of coastal seas of China to confirm the effectiveness of the proposed method. In addition, we also show its online updated characteristics.

##### Abstract (translated by Google)
本文采用长时间短时记忆（LSTM）预测海面温度（SST），这是我们第一次尝试使用递归神经网络来解决SST预测问题，并做出一周一次每月预测。我们将SST预测问题制定为时间序列回归问题。 LSTM是一种特殊的递归神经网络，它将门机制引入到香草RNN中，以防止消失或爆炸的梯度问题。对时间序列数据的时间关系进行建模具有很强的能力，能很好地处理长期依赖性问题。所提出的网络结构由两层构成：LSTM层和全连接密集层。利用LSTM层对时间序列关系进行建模。全连接层被用来映射LSTM层的输出到最终的预测。我们通过实验来探索这种建筑的最佳设置，并报告中国沿海的准确性，以证实所提方法的有效性。另外，我们还展示了它的在线更新特性。

##### URL
[https://arxiv.org/abs/1705.06861](https://arxiv.org/abs/1705.06861)

##### PDF
[https://arxiv.org/pdf/1705.06861](https://arxiv.org/pdf/1705.06861)

