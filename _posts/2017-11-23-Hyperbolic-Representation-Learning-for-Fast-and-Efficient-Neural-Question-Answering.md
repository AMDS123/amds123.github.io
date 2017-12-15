---
layout: post
title: "Hyperbolic Representation Learning for Fast and Efficient Neural Question Answering"
date: 2017-11-23 05:54:17
categories: arXiv_CL
tags: arXiv_CL QA Attention GAN Embedding CNN Represenation_Learning RNN Deep_Learning Relation
author: Yi Tay, Luu Anh Tuan, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
The dominant neural architectures in question answer retrieval are based on recurrent or convolutional encoders configured with complex word matching layers. Given that recent architectural innovations are mostly new word interaction layers or attention-based matching mechanisms, it seems to be a well-established fact that these components are mandatory for good performance. Unfortunately, the memory and computation cost incurred by these complex mechanisms are undesirable for practical applications. As such, this paper tackles the question of whether it is possible to achieve competitive performance with simple neural architectures. We propose a simple but novel deep learning architecture for fast and efficient question-answer ranking and retrieval. More specifically, our proposed model, \textsc{HyperQA}, is a parameter efficient neural network that outperforms other parameter intensive models such as Attentive Pooling BiLSTMs and Multi-Perspective CNNs on multiple QA benchmarks. The novelty behind \textsc{HyperQA} is a pairwise ranking objective that models the relationship between question and answer embeddings in Hyperbolic space instead of Euclidean space. This empowers our model with a self-organizing ability and enables automatic discovery of latent hierarchies while learning embeddings of questions and answers. Our model requires no feature engineering, no similarity matrix matching, no complicated attention mechanisms nor over-parameterized layers and yet outperforms and remains competitive to many models that have these functionalities on multiple benchmarks.

##### Abstract (translated by Google)
问题中主要的神经架构回答检索是基于配置有复杂的字匹配层的递归或卷积编码器。鉴于最近的架构创新主要是新的词汇交互层或基于注意力的匹配机制，所以这些组件对于良好的性能来说是强制性的，似乎是一个公认的事实。不幸的是，由这些复杂机制引起的存储和计算成本在实际应用中是不希望的。因此，本文解决了是否有可能通过简单的神经架构实现竞争力的问题。我们提出了一个简单而新颖的深度学习体系结构，可以快速高效地进行问答排序和检索。更具体地说，我们提出的模型\ textsc {HyperQA}是一个参数高效的神经网络，它优于其他参数密集型模型，如多个QA基准上的注意力集中BiLSTM和多视角CNN。 \ textsc {HyperQA}背后的新颖性是一个成对的排序目标，用于模拟双曲空间中的问答嵌入之间的关系而不是欧几里德空间。这使我们的模型具有自我组织的能力，并能够自动发现潜在层次结构，同时学习问题和答案的嵌入。我们的模型不需要特征工程，没有相似性矩阵匹配，没有复杂的注意机制，也没有过度参数化的层，但性能优于许多在多个基准上具有这些功能的模型。

##### URL
[https://arxiv.org/abs/1707.07847](https://arxiv.org/abs/1707.07847)

##### PDF
[https://arxiv.org/pdf/1707.07847](https://arxiv.org/pdf/1707.07847)

