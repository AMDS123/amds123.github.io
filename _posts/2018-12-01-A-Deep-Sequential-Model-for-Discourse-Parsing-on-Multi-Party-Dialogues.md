---
layout: post
title: "A Deep Sequential Model for Discourse Parsing on Multi-Party Dialogues"
date: 2018-12-01 08:13:48
categories: arXiv_AI
tags: arXiv_AI Sentiment Classification Prediction Relation
author: Zhouxing Shi, Minlie Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Discourse structures are beneficial for various NLP tasks such as dialogue understanding, question answering, sentiment analysis, and so on. This paper presents a deep sequential model for parsing discourse dependency structures of multi-party dialogues. The proposed model aims to construct a discourse dependency tree by predicting dependency relations and constructing the discourse structure jointly and alternately. It makes a sequential scan of the Elementary Discourse Units (EDUs) in a dialogue. For each EDU, the model decides to which previous EDU the current one should link and what the corresponding relation type is. The predicted link and relation type are then used to build the discourse structure incrementally with a structured encoder. During link prediction and relation classification, the model utilizes not only local information that represents the concerned EDUs, but also global information that encodes the EDU sequence and the discourse structure that is already built at the current step. Experiments show that the proposed model outperforms all the state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00176](http://arxiv.org/abs/1812.00176)

##### PDF
[http://arxiv.org/pdf/1812.00176](http://arxiv.org/pdf/1812.00176)

