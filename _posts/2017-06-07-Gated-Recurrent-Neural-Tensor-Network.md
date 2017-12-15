---
layout: post
title: "Gated Recurrent Neural Tensor Network"
date: 2017-06-07 15:05:39
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Relation
author: Andros Tjandra, Sakriani Sakti, Ruli Manurung, Mirna Adriani, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs), which are a powerful scheme for modeling temporal and sequential data need to capture long-term dependencies on datasets and represent them in hidden layers with a powerful model to capture more information from inputs. For modeling long-term dependencies in a dataset, the gating mechanism concept can help RNNs remember and forget previous information. Representing the hidden layers of an RNN with more expressive operations (i.e., tensor products) helps it learn a more complex relationship between the current input and the previous hidden layer information. These ideas can generally improve RNN performances. In this paper, we proposed a novel RNN architecture that combine the concepts of gating mechanism and the tensor product into a single model. By combining these two concepts into a single RNN, our proposed models learn long-term dependencies by modeling with gating units and obtain more expressive and direct interaction between input and hidden layers using a tensor product on 3-dimensional array (tensor) weight parameters. We use Long Short Term Memory (LSTM) RNN and Gated Recurrent Unit (GRU) RNN and combine them with a tensor product inside their formulations. Our proposed RNNs, which are called a Long-Short Term Memory Recurrent Neural Tensor Network (LSTMRNTN) and Gated Recurrent Unit Recurrent Neural Tensor Network (GRURNTN), are made by combining the LSTM and GRU RNN models with the tensor product. We conducted experiments with our proposed models on word-level and character-level language modeling tasks and revealed that our proposed models significantly improved their performance compared to our baseline models.

##### Abstract (translated by Google)
递归神经网络（RNNs）是建立时间序列和时序数据的强大方案，需要捕捉数据集的长期依赖关系，并使用强大的模型将其表示为隐藏层，以从输入中捕获更多的信息。为了建模数据集中的长期依赖关系，门控机制概念可以帮助RNN记住并忘记以前的信息。用更具表达性的操作（即张量产品）来表示RNN的隐藏层有助于它学习当前输入与先前隐藏层信息之间更复杂的关系。这些想法通常可以提高RNN的性能。在本文中，我们提出了一种新的RNN架构，将门控机制和张量产品的概念结合成一个单一的模型。通过将这两个概念结合到一个RNN中，我们提出的模型通过使用门控单元进行建模来学习长期依赖性，并且使用三维阵列（张量）权重参数上的张量积来获得输入层和隐藏层之间的更具表现力和直接的相互作用。我们使用长期短期记忆（LSTM）RNN和门控循环单元（GRU）RNN，并将它们与其配方中的张量积相结合。通过将LSTM和GRU RNN模型与张量积相结合，我们提出了被称为长 - 短期记忆递归神经张量网络（LSTMRNTN）和门控递归单元递归神经张量网络（GRURNTN）的RNN。我们对我们提出的字级和特征级语言建模任务模型进行了实验，结果表明，与我们的基准模型相比，我们提出的模型显着提高了他们的性能。

##### URL
[https://arxiv.org/abs/1706.02222](https://arxiv.org/abs/1706.02222)

##### PDF
[https://arxiv.org/pdf/1706.02222](https://arxiv.org/pdf/1706.02222)

