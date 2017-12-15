---
layout: post
title: "Neural Structural Correspondence Learning for Domain Adaptation"
date: 2017-06-17 22:30:57
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Embedding Represenation_Learning Classification
author: Yftah Ziser, Roi Reichart
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation, adapting models from domains rich in labeled training data to domains poor in such data, is a fundamental NLP challenge. We introduce a neural network model that marries together ideas from two prominent strands of research on domain adaptation through representation learning: structural correspondence learning (SCL, (Blitzer et al., 2006)) and autoencoder neural networks. Particularly, our model is a three-layer neural network that learns to encode the nonpivot features of an input example into a low-dimensional representation, so that the existence of pivot features (features that are prominent in both domains and convey useful information for the NLP task) in the example can be decoded from that representation. The low-dimensional representation is then employed in a learning algorithm for the task. Moreover, we show how to inject pre-trained word embeddings into our model in order to improve generalization across examples with similar pivot features. On the task of cross-domain product sentiment classification (Blitzer et al., 2007), consisting of 12 domain pairs, our model outperforms both the SCL and the marginalized stacked denoising autoencoder (MSDA, (Chen et al., 2012)) methods by 3.77% and 2.17% respectively, on average across domain pairs.

##### Abstract (translated by Google)
领域适应，从富有标记的训练数据领域的模型适应到这些数据较差的领域，是一个基本的NLP挑战。我们引入了一个神经网络模型，通过表示学习结合两个领域适应研究的主要思路：结构对应学习（SCL，（Blitzer et al。，2006））和自动编码器神经网络。特别是，我们的模型是一个三层神经网络，学习将输入示例的非枢轴特征编码为低维表示，以便枢轴特征的存在（特征在两个域中都是显着的，并且为NLP任务）可以从该表示中解码。然后将低维表示用于任务的学习算法中。此外，我们展示了如何将预先训练的词嵌入注入到我们的模型中，以便改善具有相似主要特征的示例的泛化。在由12个域组成的跨领域产品情感分类（Blitzer et al。，2007）的任务中，我们的模型优于SCL和边缘化堆叠去噪自动编码器（MSDA，（Chen et al。，2012））分别下降了3.77％和2.17％。

##### URL
[https://arxiv.org/abs/1610.01588](https://arxiv.org/abs/1610.01588)

##### PDF
[https://arxiv.org/pdf/1610.01588](https://arxiv.org/pdf/1610.01588)

