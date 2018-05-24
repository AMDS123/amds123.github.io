---
layout: post
title: "Excitation Dropout: Encouraging Plasticity in Deep Neural Networks"
date: 2018-05-23 12:32:41
categories: arXiv_CV
tags: arXiv_CV Salient Prediction Recognition
author: Andrea Zunino, Sarah Adel Bargal, Pietro Morerio, Jianming Zhang, Stan Sclaroff, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a guided dropout regularizer for deep networks based on the evidence of a network prediction: the firing of neurons in specific paths. In this work, we utilize the evidence at each neuron to determine the probability of dropout, rather than dropping out neurons uniformly at random as in standard dropout. In essence, we dropout with higher probability those neurons which contribute more to decision making at training time. This approach penalizes high saliency neurons that are most relevant for model prediction, i.e. those having stronger evidence. By dropping such high-saliency neurons, the network is forced to learn alternative paths in order to maintain loss minimization, resulting in a plasticity-like behavior, a characteristic of human brains too. We demonstrate better generalization ability, an increased utilization of network neurons, and a higher resilience to network compression using several metrics over four image/video recognition benchmarks.

##### Abstract (translated by Google)
我们提出了一个基于网络预测证据的深度网络的指导辍学调节器：在特定路径中发射神经元。在这项工作中，我们利用每个神经元的证据来确定辍学的概率，而不是像标准辍学生那样随机剔除神经元。实质上，我们以更高的概率辍学那些在训练时间对决策做出更多贡献的神经元。该方法惩罚与模型预测最相关的高显着性神经元，即那些具有更强证据的神经元。通过放弃这样的高显着性神经元，网络被迫学习替代路径以维持损失最小化，导致类似可塑性的行为，也是人类大脑的特征。我们展示了更好的泛化能力，提高了网络神经元的利用率，并且在四个图像/视频识别基准上使用多个度量标准提高了对网络压缩的恢复能力。

##### URL
[http://arxiv.org/abs/1805.09092](http://arxiv.org/abs/1805.09092)

##### PDF
[http://arxiv.org/pdf/1805.09092](http://arxiv.org/pdf/1805.09092)

