---
layout: post
title: "Learning Hidden Unit Contributions for Unsupervised Acoustic Model Adaptation"
date: 2016-07-13 17:47:07
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Pawel Swietojanski, Jinyu Li, Steve Renals
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a broad study on the adaptation of neural network acoustic models by means of learning hidden unit contributions (LHUC) -- a method that linearly re-combines hidden units in a speaker- or environment-dependent manner using small amounts of unsupervised adaptation data. We also extend LHUC to a speaker adaptive training (SAT) framework that leads to a more adaptable DNN acoustic model, working both in a speaker-dependent and a speaker-independent manner, without the requirements to maintain auxiliary speaker-dependent feature extractors or to introduce significant speaker-dependent changes to the DNN structure. Through a series of experiments on four different speech recognition benchmarks (TED talks, Switchboard, AMI meetings, and Aurora4) comprising 270 test speakers, we show that LHUC in both its test-only and SAT variants results in consistent word error rate reductions ranging from 5% to 23% relative depending on the task and the degree of mismatch between training and test data. In addition, we have investigated the effect of the amount of adaptation data per speaker, the quality of unsupervised adaptation targets, the complementarity to other adaptation techniques, one-shot adaptation, and an extension to adapting DNNs trained in a sequence discriminative manner.

##### Abstract (translated by Google)
这项工作提出了一个广泛的研究神经网络声学模型的学习方法，通过学习隐藏单位贡献（LHUC） - 一种方法，线性地重新组合隐藏单元的扬声器或环境依赖的方式使用少量的无监督的适应数据。我们还将LHUC扩展到说话人自适应训练（SAT）框架，导致DNN声学模型更具适应性，既可以以说话者依赖的方式也可以以说话者无关的方式工作，而不需要保持辅助的依赖于说话者的特征提取器或对DNN结构引入重要的说话者相关变化。通过对包含270个测试说话人的四种不同语音识别基准（TED会谈，交换机，AMI会议和Aurora4）进行一系列实验，我们证明LHUC在其仅有测试和SAT两种版本中的结果是一致的误码率降低训练和测试数据之间的不匹配程度取决于任务的5％至23％。此外，我们还研究了每个说话人的适应数据量，无监督的适应目标的质量，与其他适应技术的互补性，一次适应，以及对以序列判别方式训练的DNN进行适应的扩展的影响。

##### URL
[https://arxiv.org/abs/1601.02828](https://arxiv.org/abs/1601.02828)

##### PDF
[https://arxiv.org/pdf/1601.02828](https://arxiv.org/pdf/1601.02828)

