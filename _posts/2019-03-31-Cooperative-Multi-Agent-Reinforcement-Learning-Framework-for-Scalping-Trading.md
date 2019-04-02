---
layout: post
title: "Cooperative Multi-Agent Reinforcement Learning Framework for Scalping Trading"
date: 2019-03-31 16:15:42
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Uk Jo, Taehyun Jo, Wanjun Kim, Iljoo Yoon, Dongseok Lee, Seungho Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We explore deep Reinforcement Learning(RL) algorithms for scalping trading and knew that there is no appropriate trading gym and agent examples. Thus we propose gym and agent like Open AI gym in finance. Not only that, we introduce new RL framework based on our hybrid algorithm which leverages between supervised learning and RL algorithm and uses meaningful observations such order book and settlement data from experience watching scalpers trading. That is very crucial information for traders behavior to be decided. To feed these data into our model, we use spatio-temporal convolution layer, called Conv3D for order book data and temporal CNN, called Conv1D for settlement data. Those are preprocessed by episode filter we developed. Agent consists of four sub agents divided to clarify their own goal to make best decision. Also, we adopted value and policy based algorithm to our framework. With these features, we could make agent mimic scalpers as much as possible. In many fields, RL algorithm has already begun to transcend human capabilities in many domains. This approach could be a starting point to beat human in the financial stock market, too and be a good reference for anyone who wants to design RL algorithm in real world domain. Finally, weexperiment our framework and gave you experiment progress.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00441](http://arxiv.org/abs/1904.00441)

##### PDF
[http://arxiv.org/pdf/1904.00441](http://arxiv.org/pdf/1904.00441)

