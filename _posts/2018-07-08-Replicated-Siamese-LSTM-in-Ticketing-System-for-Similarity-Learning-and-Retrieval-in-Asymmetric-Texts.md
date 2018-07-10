---
layout: post
title: "Replicated Siamese LSTM in Ticketing System for Similarity Learning and Retrieval in Asymmetric Texts"
date: 2018-07-08 17:33:43
categories: arXiv_CL
tags: arXiv_CL Knowledge RNN
author: Pankaj Gupta, Bernt Andrassy, Hinrich Sch&#xfc;tze
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of our industrial ticketing system is to retrieve a relevant solution for an input query, by matching with historical tickets stored in knowledge base. A query is comprised of subject and description, while a historical ticket consists of subject, description and solution. To retrieve a relevant solution, we use textual similarity paradigm to learn similarity in the query and historical tickets. The task is challenging due to significant term mismatch in the query and ticket pairs of asymmetric lengths, where subject is a short text but description and solution are multi-sentence texts. We present a novel Replicated Siamese LSTM model to learn similarity in asymmetric text pairs, that gives 22% and 7% gain (Accuracy@10) for retrieval task, respectively over unsupervised and supervised baselines. We also show that the topic and distributed semantic features for short and long texts improved both similarity learning and retrieval.

##### Abstract (translated by Google)
我们的工业票务系统的目标是通过匹配存储在知识库中的历史票证来检索输入查询的相关解决方案。查询由主题和描述组成，而历史票据由主题，描述和解决方案组成。为了检索相关解决方案，我们使用文本相似性范例来学习查询和历史票证中的相似性。由于查询和不对称长度的票对中的重要术语不匹配，任务具有挑战性，其中主题是短文本，但描述和解决方案是多句文本。我们提出了一种新的复制暹罗LSTM模型来学习不对称文本对的相似性，分别在无监督和监督基线上为检索任务提供22％和7％的增益（Accuracy @ 10）。我们还表明，短文本和长文本的主题和分布式语义特征改进了相似性学习和检索。

##### URL
[http://arxiv.org/abs/1807.02854](http://arxiv.org/abs/1807.02854)

##### PDF
[http://arxiv.org/pdf/1807.02854](http://arxiv.org/pdf/1807.02854)

