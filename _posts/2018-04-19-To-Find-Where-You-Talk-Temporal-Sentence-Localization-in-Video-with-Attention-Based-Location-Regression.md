---
layout: post
title: "To Find Where You Talk: Temporal Sentence Localization in Video with Attention Based Location Regression"
date: 2018-04-19 06:48:40
categories: arXiv_CV
tags: arXiv_CV Attention Caption RNN
author: Yitian Yuan, Tao Mei, Wenwu Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Given an untrimmed video and a sentence description, temporal sentence localization aims to automatically determine the start and end points of the described sentence within the video. The problem is challenging as it needs the understanding of both video and sentence. Existing research predominantly employs a costly "scan and localize" framework, neglecting the global video context and the specific details within sentences which play as critical issues for this problem. In this paper, we propose a novel Attention Based Location Regression (ABLR) approach to solve the temporal sentence localization from a global perspective. Specifically, to preserve the context information, ABLR first encodes both video and sentence via Bidirectional LSTM networks. Then, a multi-modal co-attention mechanism is introduced to generate not only video attention which reflects the global video structure, but also sentence attention which highlights the crucial details for temporal localization. Finally, a novel attention based location regression network is designed to predict the temporal coordinates of sentence query from the previous attention. ABLR is jointly trained in an end-to-end manner. Comprehensive experiments on ActivityNet Captions and TACoS datasets demonstrate both the effectiveness and the efficiency of the proposed ABLR approach.

##### Abstract (translated by Google)
给定未修剪的视频和句子描述，时间句子定位旨在自动确定视频内所描述的句子的起点和终点。这个问题具有挑战性，因为它需要理解视频和句子。现有的研究主要采用昂贵的“扫描和本地化”框架，忽略了全局视频环境和句子中的具体细节，这些问题是这个问题的关键问题。在本文中，我们提出了一种新的基于注意力的位置回归（ABLR）方法，从全局角度解决时间句子定位问题。具体来说，为了保留上下文信息，ABLR首先通过双向LSTM网络对视频和句子进行编码。然后，引入多模态共同关注机制不仅产生反映全局视频结构的视频注意力，而且产生突出时间定位的关键细节的句子注意力。最后，设计了一种新的基于注意力的位置回归网络来预测先前注意力的句子查询的时间坐标。 ABLR以端到端的方式共同接受培训。 ActivityNet Captions和TACoS数据集的综合实验证明了所提出的ABLR方法的有效性和效率。

##### URL
[https://arxiv.org/abs/1804.07014](https://arxiv.org/abs/1804.07014)

##### PDF
[https://arxiv.org/pdf/1804.07014](https://arxiv.org/pdf/1804.07014)

