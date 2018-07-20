---
layout: post
title: "A Capsule based Approach for Polyphonic Sound Event Detection"
date: 2018-07-19 13:58:32
categories: arXiv_SD
tags: arXiv_SD CNN RNN Deep_Learning Detection
author: Yaming Liu, Jian Tang, Yan Song, Lirong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Polyphonic sound event detection (polyphonic SED) is an interesting but challenging task due to the concurrence of multiple sound events. Recently, SED methods based on convolutional neural networks (CNN) and recurrent neural networks (RNN) have shown promising performance. Generally, CNN are designed for local feature extraction while RNN are used to model the temporal dependency among these local features. Despite their success, it is still insufficient for existing deep learning techniques to separate individual sound event from their mixture, largely due to the overlapping characteristic of features. Motivated by the success of Capsule Networks (CapsNet), we propose a more suitable capsule based approach for polyphonic SED. Specifically, several capsule layers are designed to effectively select representative frequency bands for each individual sound event. The temporal dependency of capsule's outputs is then modeled by a RNN. And a dynamic threshold method is proposed for making the final decision based on RNN outputs. Experiments on the TUT-SED Synthetic 2016 dataset show that the proposed approach obtains an F1-score of 68.8% and an error rate of 0.45, outperforming the previous state-of-the-art method of 66.4% and 0.48, respectively.

##### Abstract (translated by Google)
由于多个声音事件的同时发生，复音声音事件检测（复音SED）是一项有趣但具有挑战性的任务。最近，基于卷积神经网络（CNN）和递归神经网络（RNN）的SED方法已经显示出有希望的性能。通常，CNN被设计用于局部特征提取，而RNN用于模拟这些局部特征之间的时间依赖性。尽管取得了成功，但现有的深度学习技术仍然不足以将个别声音事件与其混合物分开，主要是由于特征的重叠特征。在Capsule Networks（CapsNet）成功的推动下，我们提出了一种更合适的基于胶囊的复音SED方法。具体地，设计若干胶囊层以有效地为每个单独的声音事件选择代表性频带。然后，胶囊的输出的时间依赖性由RNN建模。并提出了一种基于RNN输出的最终决策动态阈值方法。在TUT-SED Synthetic 2016数据集上的实验表明，所提出的方法获得了68.8％的F1得分和0.45的错误率，分别优于先前的66.4％和0.48的最新方法。

##### URL
[http://arxiv.org/abs/1807.07436](http://arxiv.org/abs/1807.07436)

##### PDF
[http://arxiv.org/pdf/1807.07436](http://arxiv.org/pdf/1807.07436)

