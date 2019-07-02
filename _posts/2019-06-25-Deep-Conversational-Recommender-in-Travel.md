---
layout: post
title: "Deep Conversational Recommender in Travel"
date: 2019-06-25 04:39:26
categories: arXiv_AI
tags: arXiv_AI CNN Relation Recommendation
author: Lizi Liao, Ryuichi Takanobu, Yunshan Ma, Xun Yang, Minlie Huang, Tat-Seng Chua
mathjax: true
---

* content
{:toc}

##### Abstract
When traveling to a foreign country, we are often in dire need of an intelligent conversational agent to provide instant and informative responses to our various queries. However, to build such a travel agent is non-trivial. First of all, travel naturally involves several sub-tasks such as hotel reservation, restaurant recommendation and taxi booking etc, which invokes the need for global topic control. Secondly, the agent should consider various constraints like price or distance given by the user to recommend an appropriate venue. In this paper, we present a Deep Conversational Recommender (DCR) and apply to travel. It augments the sequence-to-sequence (seq2seq) models with a neural latent topic component to better guide response generation and make the training easier. To consider the various constraints for venue recommendation, we leverage a graph convolutional network (GCN) based approach to capture the relationships between different venues and the match between venue and dialog context. For response generation, we combine the topic-based component with the idea of pointer networks, which allows us to effectively incorporate recommendation results. We perform extensive evaluation on a multi-turn task-oriented dialog dataset in travel domain and the results show that our method achieves superior performance as compared to a wide range of baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00710](http://arxiv.org/abs/1907.00710)

##### PDF
[http://arxiv.org/pdf/1907.00710](http://arxiv.org/pdf/1907.00710)

