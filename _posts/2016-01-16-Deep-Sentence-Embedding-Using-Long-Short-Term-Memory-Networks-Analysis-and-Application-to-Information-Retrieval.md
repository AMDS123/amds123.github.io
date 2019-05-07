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


##### URL
[https://arxiv.org/abs/1502.06922](https://arxiv.org/abs/1502.06922)

##### PDF
[https://arxiv.org/pdf/1502.06922](https://arxiv.org/pdf/1502.06922)

