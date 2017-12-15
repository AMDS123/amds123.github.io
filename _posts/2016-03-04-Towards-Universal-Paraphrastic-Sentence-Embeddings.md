---
layout: post
title: "Towards Universal Paraphrastic Sentence Embeddings"
date: 2016-03-04 20:54:30
categories: arXiv_CL
tags: arXiv_CL Sentiment GAN Sentiment_Classification Embedding RNN Classification
author: John Wieting, Mohit Bansal, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of learning general-purpose, paraphrastic sentence embeddings based on supervision from the Paraphrase Database (Ganitkevitch et al., 2013). We compare six compositional architectures, evaluating them on annotated textual similarity datasets drawn both from the same distribution as the training data and from a wide range of other domains. We find that the most complex architectures, such as long short-term memory (LSTM) recurrent neural networks, perform best on the in-domain data. However, in out-of-domain scenarios, simple architectures such as word averaging vastly outperform LSTMs. Our simplest averaging model is even competitive with systems tuned for the particular tasks while also being extremely efficient and easy to use. In order to better understand how these architectures compare, we conduct further experiments on three supervised NLP tasks: sentence similarity, entailment, and sentiment classification. We again find that the word averaging models perform well for sentence similarity and entailment, outperforming LSTMs. However, on sentiment classification, we find that the LSTM performs very strongly-even recording new state-of-the-art performance on the Stanford Sentiment Treebank. We then demonstrate how to combine our pretrained sentence embeddings with these supervised tasks, using them both as a prior and as a black box feature extractor. This leads to performance rivaling the state of the art on the SICK similarity and entailment tasks. We release all of our resources to the research community with the hope that they can serve as the new baseline for further work on universal sentence embeddings.

##### Abstract (translated by Google)
我们考虑通过释义数据库（Ganitkevitch et al。，2013）的监督来学习通用目的句，句法嵌入句的问题。我们比较了六种组合体系结构，从注释的文本相似性数据集上对它们进行评估，这些数据集既来自与培训数据相同的分布，也来自各种其他领域。我们发现，最复杂的架构，如长期短期记忆（LSTM）递归神经网络，在域内数据上表现最好。但是，在域外场景中，简单的结构（如字平均值）远远优于LSTM。我们最简单的平均模型甚至可以与针对特定任务调整的系统竞争，同时也非常高效且易于使用。为了更好地理解这些体系结构如何比较，我们对三个有监督的NLP任务进行了进一步的实验：句子相似度，蕴涵度和情感分类。我们再次发现，平均模型这个词在句子相似性和蕴涵方面表现良好，超越了LSTMs。然而，在情绪分类方面，我们发现LSTM在斯坦福情绪树上表现非常强劲，甚至录制了最新的艺术表现。然后，我们演示如何将预训练语句嵌入与这些监督任务相结合，将它们同时用作事先和黑箱特征提取器。这导致性能与SICK相似性和包容性任务相媲美。我们将所有的资源释放给研究团体，希望他们能够成为进一步研究普遍语句嵌入的新基准。

##### URL
[https://arxiv.org/abs/1511.08198](https://arxiv.org/abs/1511.08198)

##### PDF
[https://arxiv.org/pdf/1511.08198](https://arxiv.org/pdf/1511.08198)

