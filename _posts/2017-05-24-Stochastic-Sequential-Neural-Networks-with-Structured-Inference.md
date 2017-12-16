---
layout: post
title: "Stochastic Sequential Neural Networks with Structured Inference"
date: 2017-05-24 10:52:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference RNN Recognition
author: Hao Liu, Haoli Bai, Lirong He, Zenglin Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised structure learning in high-dimensional time series data has attracted a lot of research interests. For example, segmenting and labelling high dimensional time series can be helpful in behavior understanding and medical diagnosis. Recent advances in generative sequential modeling have suggested to combine recurrent neural networks with state space models (e.g., Hidden Markov Models). This combination can model not only the long term dependency in sequential data, but also the uncertainty included in the hidden states. Inheriting these advantages of stochastic neural sequential models, we propose a structured and stochastic sequential neural network, which models both the long-term dependencies via recurrent neural networks and the uncertainty in the segmentation and labels via discrete random variables. For accurate and efficient inference, we present a bi-directional inference network by reparamterizing the categorical segmentation and labels with the recent proposed Gumbel-Softmax approximation and resort to the Stochastic Gradient Variational Bayes. We evaluate the proposed model in a number of tasks, including speech modeling, automatic segmentation and labeling in behavior understanding, and sequential multi-objects recognition. Experimental results have demonstrated that our proposed model can achieve significant improvement over the state-of-the-art methods.

##### Abstract (translated by Google)
高维时间序列数据中的无监督结构学习吸引了大量的研究兴趣。例如，高维时间序列的分割和标记可以有助于行为理解和医学诊断。生成序贯建模的最新进展已经提出将递归神经网络与状态空间模型（例如，隐马尔可夫模型）相结合。这种组合不仅可以模拟顺序数据中的长期依赖性，还可以模拟隐藏状态中包含的不确定性。继承了随机神经网络模型的这些优点，我们提出了一种结构化的随机序贯神经网络，它通过递归神经网络建立长期依赖关系，并通过离散随机变量对分割和标记中的不确定性进行建模。为了进行准确而有效的推理，我们提出了一个双向推理网络，通过用最近提出的Gumbel-Softmax逼近和求解随机梯度变分贝叶斯来重新分类分类和标签。我们在许多任务中评估所提出的模型，包括语音建模，行为理解中的自动分割和标记，以及顺序多目标识别。实验结果表明，我们提出的模型可以比现有技术方法有显着的改进。

##### URL
[https://arxiv.org/abs/1705.08695](https://arxiv.org/abs/1705.08695)

##### PDF
[https://arxiv.org/pdf/1705.08695](https://arxiv.org/pdf/1705.08695)

