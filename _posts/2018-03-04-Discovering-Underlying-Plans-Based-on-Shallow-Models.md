---
layout: post
title: "Discovering Underlying Plans Based on Shallow Models"
date: 2018-03-04 03:18:22
categories: arXiv_AI
tags: arXiv_AI RNN Recognition
author: Hankz Hankui Zhuo, Yantian Zha, Subbarao Kambhampati
mathjax: true
---

* content
{:toc}

##### Abstract
Plan recognition aims to discover target plans (i.e., sequences of actions) behind observed actions, with history plan libraries or domain models in hand. Previous approaches either discover plans by maximally "matching" observed actions to plan libraries, assuming target plans are from plan libraries, or infer plans by executing domain models to best explain the observed actions, assuming that complete domain models are available. In real world applications, however, target plans are often not from plan libraries, and complete domain models are often not available, since building complete sets of plans and complete domain models are often difficult or expensive. In this paper we view plan libraries as corpora and learn vector representations of actions using the corpora, we then discover target plans based on the vector representations. Specifically, we propose two approaches, DUP and RNNPlanner, to discover target plans based on vector representations of actions. DUP explores the EM-style framework to capture local contexts of actions and discover target plans by optimizing the probability of target plans, while RNNPlanner aims to leverage long-short term contexts of actions based on RNNs (recurrent neural networks) framework to help recognize target plans. In the experiments, we empirically show that our approaches are capable of discovering underlying plans that are not from plan libraries, without requiring domain models provided. We demonstrate the effectiveness of our approaches by comparing its performance to traditional plan recognition approaches in three planning domains. We also compare DUP and RNNPlanner to see their advantages and disadvantages.

##### Abstract (translated by Google)
计划识别的目的是发现观察到的行动背后的目标计划（即行为序列），以及历史计划库或领域模型。以前的方法要么通过最大程度地将观察到的行为“匹配”到计划库，假定目标计划来自计划库，要么通过执行领域模型来推断计划以最好地解释观察到的行为，假设完整的领域模型可用，则发现计划。然而，在现实世界的应用中，目标计划通常不是来自计划库，完整的领域模型往往不可用，因为构建完整的计划集和完整的领域模型通常很困难或昂贵。在本文中，我们将计划库视为语料库，并使用语料库学习行为的向量表示，然后根据向量表示发现目标计划。具体来说，我们提出了两种方法，DUP和RNNPlanner，根据行动的向量表示发现目标计划。 DUP通过优化目标计划的可能性来探索EM风格的框架以捕捉行动的本地情境并发现目标计划，而RNNPlanner旨在利用基于RNN（循环神经网络）框架的长期短期行为背景来帮助识别目标计划。在实验中，我们凭经验证明，我们的方法能够发现不是来自计划库的底层计划，也不需要提供域模型。我们通过比较其在三个规划领域中的传统计划识别方法的表现来证明我们方法的有效性。我们还比较DUP和RNNPlanner以查看它们的优点和缺点。

##### URL
[http://arxiv.org/abs/1803.02208](http://arxiv.org/abs/1803.02208)

##### PDF
[http://arxiv.org/pdf/1803.02208](http://arxiv.org/pdf/1803.02208)

