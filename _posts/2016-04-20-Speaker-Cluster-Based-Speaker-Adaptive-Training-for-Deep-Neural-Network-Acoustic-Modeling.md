---
layout: post
title: "Speaker Cluster-Based Speaker Adaptive Training for Deep Neural Network Acoustic Modeling"
date: 2016-04-20 20:10:41
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Wei Chu, Ruxin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
A speaker cluster-based speaker adaptive training (SAT) method under deep neural network-hidden Markov model (DNN-HMM) framework is presented in this paper. During training, speakers that are acoustically adjacent to each other are hierarchically clustered using an i-vector based distance metric. DNNs with speaker dependent layers are then adaptively trained for each cluster of speakers. Before decoding starts, an unseen speaker in test set is matched to the closest speaker cluster through comparing i-vector based distances. The previously trained DNN of the matched speaker cluster is used for decoding utterances of the test speaker. The performance of the proposed method on a large vocabulary spontaneous speech recognition task is evaluated on a training set of with 1500 hours of speech, and a test set of 24 speakers with 1774 utterances. Comparing to a speaker independent DNN with a baseline word error rate of 11.6%, a relative 6.8% reduction in word error rate is observed from the proposed method.

##### Abstract (translated by Google)
本文提出了一种基于深度神经网络隐马尔可夫模型（DNN-HMM）框架的基于说话人聚类的说话人自适应训练（SAT）方法。在训练期间，使用基于i向量的距离度量来对彼此在声学上相邻的说话者进行分层聚类。然后自适应地训练具有说话者依赖层的DNN以用于每个说话者群。在解码开始之前，通过比较基于i向量的距离来将测试集中的看不见的说话者与最近的说话者聚类匹配。匹配的扬声器集群的先前训练的DNN被用于解码测试扬声器的话语。本文提出的方法在大型词汇自发语音识别任务上的表现，在1500小时的语音训练集上进行评估，24人的测试集以1774个语音进行评估。与基线误码率为11.6％的说话者无关DNN相比，该方法观察到的误码率降低了6.8％。

##### URL
[https://arxiv.org/abs/1604.06113](https://arxiv.org/abs/1604.06113)

##### PDF
[https://arxiv.org/pdf/1604.06113](https://arxiv.org/pdf/1604.06113)

