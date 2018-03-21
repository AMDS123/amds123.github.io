---
layout: post
title: "Variational Knowledge Graph Reasoning"
date: 2018-03-17 22:08:10
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Attention Inference Prediction Relation
author: Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring missing links in knowledge graphs (KG) has attracted a lot of attention from the research community. In this paper, we tackle a practical query answering task involving predicting the relation of a given entity pair. We frame this prediction problem as an inference problem in a probabilistic graphical model and aim at resolving it from a variational inference perspective. In order to model the relation between the query entity pair, we assume that there exist underlying latent variables (assemble of all paths connecting these two nodes) in the KG, which carries the equivalent semantics of their relation. However, due to the intractability of connections in large KGs, we propose to use variation inference to maximize the evidence lower bound. More specifically, our framework (\textsc{Diva}) is composed of three modules, i.e. a posterior approximator, a prior (path finder), and a likelihood (path reasoner). By using variational inference, we are able to incorporate them closely into a unified architecture and jointly optimize them to perform KG reasoning. With active interactions among these sub-modules, \textsc{Diva} is better at handling noise and cope with more complex reasoning scenarios. In order to evaluate our method, we conduct the experiment of the link prediction task on NELL-995 and FB15K datasets and achieve state-of-the-art performances on both datasets.

##### Abstract (translated by Google)
推断知识图中缺失的链接（KG）引起了研究界的很大关注。在本文中，我们处理一个实际的查询应答任务，涉及预测给定实体对的关系。我们将这个预测问题作为概率图模型中的推理问题来构建，并且旨在从变分推理的角度来解决它。为了对查询实体对之间的关​​系进行建模，我们假设KG中存在潜在的潜在变量（连接这两个节点的所有路径的集合），它携带它们关​​系的等价语义。然而，由于大型幼稚园的连接困难，我们建议使用变异推断来最大化证据下限。更具体地说，我们的框架（\ textsc {Diva}）由三个模块组成，即后验逼近器，先验（路径查找器）和可能性（路径推理器）。通过使用变分推理，我们能够将它们紧密地结合到一个统一的体系结构中，并联合优化它们来执行KG推理。通过这些子模块之间的主动交互，\ textsc {Diva}可以更好地处理噪音并应对更复杂的推理场景。为了评估我们的方法，我们在NELL-995和FB15K数据集上进行了链接预测任务的实验，并在两个数据集上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1803.06581](https://arxiv.org/abs/1803.06581)

##### PDF
[https://arxiv.org/pdf/1803.06581](https://arxiv.org/pdf/1803.06581)

