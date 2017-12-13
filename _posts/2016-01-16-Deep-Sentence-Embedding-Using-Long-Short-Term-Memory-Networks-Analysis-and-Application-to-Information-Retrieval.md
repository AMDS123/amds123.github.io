---
layout: post
title: "Deep Sentence Embedding Using Long Short-Term Memory Networks: Analysis and Application to Information Retrieval"
date: 2016-01-16 06:35:23
categories: arXiv_CV
tags: arXiv_CV Salient Weakly_Supervised Embedding RNN Detection Memory_Networks
author: Hamid Palangi, Li Deng, Yelong Shen, Jianfeng Gao, Xiaodong He, Jianshu Chen, Xinying Song, Rabab Ward
mathjax: true
---

* content
{:toc}

##### Abstract
This paper develops a model that addresses sentence embedding, a hot topic in current natural language processing research, using recurrent neural networks with Long Short-Term Memory (LSTM) cells. Due to its ability to capture long term memory, the LSTM-RNN accumulates increasingly richer information as it goes through the sentence, and when it reaches the last word, the hidden layer of the network provides a semantic representation of the whole sentence. In this paper, the LSTM-RNN is trained in a weakly supervised manner on user click-through data logged by a commercial web search engine. Visualization and analysis are performed to understand how the embedding process works. The model is found to automatically attenuate the unimportant words and detects the salient keywords in the sentence. Furthermore, these detected keywords are found to automatically activate different cells of the LSTM-RNN, where words belonging to a similar topic activate the same cell. As a semantic representation of the sentence, the embedding vector can be used in many different applications. These automatic keyword detection and topic allocation abilities enabled by the LSTM-RNN allow the network to perform document retrieval, a difficult language processing task, where the similarity between the query and documents can be measured by the distance between their corresponding sentence embedding vectors computed by the LSTM-RNN. On a web search task, the LSTM-RNN embedding is shown to significantly outperform several existing state of the art methods. We emphasize that the proposed model generates sentence embedding vectors that are specially useful for web document retrieval tasks. A comparison with a well known general sentence embedding method, the Paragraph Vector, is performed. The results show that the proposed method in this paper significantly outperforms it for web document retrieval task.

##### Abstract (translated by Google)
本文开发了一个解决句子嵌入的模型，这是当前自然语言处理研究中的一个热门话题，它使用具有长期短期记忆（LSTM）细胞的递归神经网络。由于LSTM-RNN能够捕捉长时记忆，因此在经过句子时积累越来越丰富的信息，当到达最后一个单词时，网络的隐藏层提供整个句子的语义表示。在本文中，LSTM-RNN以弱监督的方式训练由商业网页搜索引擎记录的用户点击数据。进行可视化和分析以了解嵌入过程如何工作。发现该模型会自动衰减不重要的单词，并检测句子中的显着关键字。此外，发现这些检测到的关键字自动激活LSTM-RNN的不同小区，其中属于相似主题的词激活同一小区。作为句子的语义表示，嵌入向量可以用于许多不同的应用。这些由LSTM-RNN实现的自动关键字检测和主题分配能力允许网络执行文档检索，这是一种难以处理的语言处理任务，查询和文档之间的相似性可以通过它们对应的文章嵌入向量之间的距离来测量LSTM-RNN。在网络搜索任务中，LSTM-RNN嵌入被示出为显着地胜过现有技术的几种方法。我们强调，所提出的模型生成句子嵌入矢量，这对于web文档检索任务是特别有用的。与众所周知的一般语句嵌入方法（段落向量）进行比较。结果表明，本文提出的方法明显优于Web文档检索任务。

##### URL
[https://arxiv.org/abs/1502.06922](https://arxiv.org/abs/1502.06922)

##### PDF
[https://arxiv.org/pdf/1502.06922](https://arxiv.org/pdf/1502.06922)

