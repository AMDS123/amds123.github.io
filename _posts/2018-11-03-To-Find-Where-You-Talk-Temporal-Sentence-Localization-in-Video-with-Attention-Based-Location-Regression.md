---
layout: post
title: "To Find Where You Talk: Temporal Sentence Localization in Video with Attention Based Location Regression"
date: 2018-11-03 06:48:06
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


##### URL
[https://arxiv.org/abs/1804.07014](https://arxiv.org/abs/1804.07014)

##### PDF
[https://arxiv.org/pdf/1804.07014](https://arxiv.org/pdf/1804.07014)

