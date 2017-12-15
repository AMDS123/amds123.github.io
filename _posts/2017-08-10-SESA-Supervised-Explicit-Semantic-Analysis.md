---
layout: post
title: "SESA: Supervised Explicit Semantic Analysis"
date: 2017-08-10 15:03:12
categories: arXiv_CL
tags: arXiv_CL Knowledge Represenation_Learning RNN
author: Dasha Bogdanova, Majid Yazdani
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years supervised representation learning has provided state of the art or close to the state of the art results in semantic analysis tasks including ranking and information retrieval. The core idea is to learn how to embed items into a latent space such that they optimize a supervised objective in that latent space. The dimensions of the latent space have no clear semantics, and this reduces the interpretability of the system. For example, in personalization models, it is hard to explain why a particular item is ranked high for a given user profile. We propose a novel model of representation learning called Supervised Explicit Semantic Analysis (SESA) that is trained in a supervised fashion to embed items to a set of dimensions with explicit semantics. The model learns to compare two objects by representing them in this explicit space, where each dimension corresponds to a concept from a knowledge base. This work extends Explicit Semantic Analysis (ESA) with a supervised model for ranking problems. We apply this model to the task of Job-Profile relevance in LinkedIn in which a set of skills defines our explicit dimensions of the space. Every profile and job are encoded to this set of skills their similarity is calculated in this space. We use RNNs to embed text input into this space. In addition to interpretability, our model makes use of the web-scale collaborative skills data that is provided by users for each LinkedIn profile. Our model provides state of the art result while it remains interpretable.

##### Abstract (translated by Google)
近年来，监督表示学习提供了包括排序和信息检索在内的语义分析任务的最新技术水平或接近现状的结果。核心思想是学习如何将项目嵌入到潜在空间中，从而优化潜在空间中的监督目标。潜在空间的维度没有明确的语义，这就降低了系统的可解释性。例如，在个性化模型中，很难解释为什么特定的项目对于给定的用户简档排名较高。我们提出了一种表达式学习的新模型，称为监督显式语义分析（SESA），它以受监督的方式进行训练，以明确的语义将项目嵌入到一组维度中。该模型学习通过在这个显式空间中表示它们来比较两个对象，其中每个维度对应于来自知识库的概念。这项工作扩展显式语义分析（ESA）与排序问题的监督模型。我们将这个模型应用于LinkedIn中Job-Profile相关性的任务，其中一组技能定义了我们明确的空间维度。每个配置文件和作业都被编码为这一套技能，在这个空间中计算相似度。我们使用RNN将文本输入嵌入到这个空间。除了可解释性外，我们的模型还利用用户为每个LinkedIn个人资料提供的网络级协作技能数据。我们的模型提供了最先进的结果，而它仍然是可解释的。

##### URL
[https://arxiv.org/abs/1708.03246](https://arxiv.org/abs/1708.03246)

##### PDF
[https://arxiv.org/pdf/1708.03246](https://arxiv.org/pdf/1708.03246)

