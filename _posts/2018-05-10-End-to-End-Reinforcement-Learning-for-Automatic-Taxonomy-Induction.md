---
layout: post
title: "End-to-End Reinforcement Learning for Automatic Taxonomy Induction"
date: 2018-05-10 16:19:14
categories: arXiv_CL
tags: arXiv_CL GAN Reinforcement_Learning
author: Yuning Mao, Xiang Ren, Jiaming Shen, Xiaotao Gu, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel end-to-end reinforcement learning approach to automatic taxonomy induction from a set of terms. While prior methods treat the problem as a two-phase task (i.e., detecting hypernymy pairs followed by organizing these pairs into a tree-structured hierarchy), we argue that such two-phase methods may suffer from error propagation, and cannot effectively optimize metrics that capture the holistic structure of a taxonomy. In our approach, the representations of term pairs are learned using multiple sources of information and used to determine \textit{which} term to select and \textit{where} to place it on the taxonomy via a policy network. All components are trained in an end-to-end manner with cumulative rewards, measured by a holistic tree metric over the training taxonomies. Experiments on two public datasets of different domains show that our approach outperforms prior state-of-the-art taxonomy induction methods up to 19.6\% on ancestor F1.

##### Abstract (translated by Google)
我们提出了一套新的端到端强化学习方法来从一组术语中自动分类归纳。尽管先前的方法将问题视为两阶段任务（即检测超上对，然后将这些对组织成树结构层次结构），但我们认为这样的两阶段方法可能遭受错误传播，并且不能有效地优化度量捕捉分类学的整体结构。在我们的方法中，术语对的表示是使用多种信息源来学习的，并且用于确定要选择的\ textit {哪个}项和\ textit {where}以通过策略网络将其放在分类上。所有组件都以端到端的方式进行培训，累积奖励通过训练分类标准上的整体树度量来衡量。在两个不同领域的公共数据集上进行的实验表明，我们的方法在祖先F1上胜过先前的最新分类学归纳方法，最高可达19.6％。

##### URL
[http://arxiv.org/abs/1805.04044](http://arxiv.org/abs/1805.04044)

##### PDF
[http://arxiv.org/pdf/1805.04044](http://arxiv.org/pdf/1805.04044)

