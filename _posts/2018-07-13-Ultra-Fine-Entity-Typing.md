---
layout: post
title: "Ultra-Fine Entity Typing"
date: 2018-07-13 04:19:03
categories: arXiv_AI
tags: arXiv_AI
author: Eunsol Choi, Omer Levy, Yejin Choi, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new entity typing task: given a sentence with an entity mention, the goal is to predict a set of free-form phrases (e.g. skyscraper, songwriter, or criminal) that describe appropriate types for the target entity. This formulation allows us to use a new type of distant supervision at large scale: head words, which indicate the type of the noun phrases they appear in. We show that these ultra-fine types can be crowd-sourced, and introduce new evaluation sets that are much more diverse and fine-grained than existing benchmarks. We present a model that can predict open types, and is trained using a multitask objective that pools our new head-word supervision with prior supervision from entity linking. Experimental results demonstrate that our model is effective in predicting entity types at varying granularity; it achieves state of the art performance on an existing fine-grained entity typing benchmark, and sets baselines for our newly-introduced datasets. Our data and model can be downloaded from: <a href="http://nlp.cs.washington.edu/entity_type">this http URL</a>

##### Abstract (translated by Google)
我们引入了一个新的实体输入任务：给定一个带有实体提及的句子，目标是预测一组描述目标实体的适当类型的自由形式短语（例如摩天大楼，词曲作者或罪犯）。这个公式允许我们大规模地使用一种新型的远程监督：头部单词，表示它们出现的名词短语的类型。我们表明这些超精细类型可以是众包的，并引入新的评估集比现有基准更加多样化和细粒度。我们提出了一个可以预测开放类型的模型，并使用多任务目标进行训练，该目标通过实体链接的先前监督汇集我们的新头字监督。实验结果表明，我们的模型能够有效地预测不同粒度的实体类型;它在现有的细粒度实体打字基准上实现了最先进的性能，并为我们新引入的数据集设置了基线。我们的数据和模型可以从以下网址下载：<a href="http://nlp.cs.washington.edu/entity_type">此http网址</a>

##### URL
[http://arxiv.org/abs/1807.04905](http://arxiv.org/abs/1807.04905)

##### PDF
[http://arxiv.org/pdf/1807.04905](http://arxiv.org/pdf/1807.04905)

