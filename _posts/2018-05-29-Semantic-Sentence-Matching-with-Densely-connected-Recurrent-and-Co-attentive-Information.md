---
layout: post
title: "Semantic Sentence Matching with Densely-connected Recurrent and Co-attentive Information"
date: 2018-05-29 11:29:56
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN Inference Relation
author: Seonhoon Kim, Jin-Hyuk Hong, Inho Kang, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence matching is widely used in various natural language tasks such as natural language inference, paraphrase identification, and question answering. For these tasks, understanding logical and semantic relationship between two sentences is required but it is yet challenging. Although attention mechanism is useful to capture the semantic relationship and to properly align the elements of two sentences, previous methods of attention mechanism simply use a summation operation which does not retain original features enough. Inspired by DenseNet, a densely connected convolutional network, we propose a densely-connected co-attentive recurrent neural network, each layer of which uses concatenated information of attentive features as well as hidden features of all the preceding recurrent layers. It enables preserving the original and the co-attentive feature information from the bottommost word embedding layer to the uppermost recurrent layer. To alleviate the problem of an ever-increasing size of feature vectors due to dense concatenation operations, we also propose to use an autoencoder after dense concatenation. We evaluate our proposed architecture on highly competitive benchmark datasets related to sentence matching. Experimental results show that our architecture, which retains recurrent and attentive features, achieves state-of-the-art performances for all the tasks.

##### Abstract (translated by Google)
句子匹配广泛用于各种自然语言任务，如自然语言推理，释义识别和问题回答。对于这些任务，理解两个句子之间的逻辑和语义关系是必需的，但它仍然具有挑战性。虽然注意机制对于捕捉语义关系和正确对齐两个句子的元素很有用，但以前的注意机制方法只是使用一种不足以保留原始特征的求和操作。受稠密连接的卷积网络DenseNet的启发，我们提出了一种密集连接的共同聚焦递归神经网络，其每一层都使用细致特征的连接信息以及所有前面的递归层的隐藏特征。它能够保留从最底层字嵌入层到最上层回归层的原始和共同注意特征信息。为了缓解由于密集级联操作导致的特征向量大小不断增加的问题，我们还提出在密集级联之后使用自编码器。我们评估我们提出的与句子匹配相关的高度竞争基准数据集上的架构。实验结果表明，我们的架构保留了经常性和细心的特征，为所有任务实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1805.11360](http://arxiv.org/abs/1805.11360)

##### PDF
[http://arxiv.org/pdf/1805.11360](http://arxiv.org/pdf/1805.11360)

