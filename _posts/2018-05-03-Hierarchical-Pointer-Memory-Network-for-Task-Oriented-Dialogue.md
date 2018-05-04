---
layout: post
title: "Hierarchical Pointer Memory Network for Task Oriented Dialogue"
date: 2018-05-03 10:52:26
categories: arXiv_CL
tags: arXiv_CL Knowledge Memory_Networks
author: Dinesh Raghu, Nikhil Gupta, Mausam
mathjax: true
---

* content
{:toc}

##### Abstract
We observe that end-to-end memory networks (MN) trained for task-oriented dialogue, such as for recommending restaurants to a user, suffer from an out-of-vocabulary (OOV) problem -- the entities returned by the Knowledge Base (KB) may not be seen by the network at training time, making it impossible for it to use them in dialogue. We propose a Hierarchical Pointer Memory Network (HyP-MN), in which the next word may be generated from the decode vocabulary or copied from a hierarchical memory maintaining KB results and previous utterances. Evaluating over the dialog bAbI tasks, we find that HyP-MN drastically outperforms MN obtaining 12% overall accuracy gains. Further analysis reveals that MN fails completely in recommending any relevant restaurant, whereas HyP-MN recommends the best next restaurant 80% of the time.

##### Abstract (translated by Google)
我们观察到，针对面向任务的对话（例如向用户推荐餐馆）训练的端对端存储器网络（MN）受到词汇外（OOV）问题的困扰 - 由知识库返回的实体（KB）在培训期间可能不会被网络看到，使其无法在对话中使用它们。我们提出了一种分层指针存储器网络（HyP-MN），其中下一个字可以从解码词汇表生成，或者从维护KB结果和先前话语的分层存储器中复制。通过评估对话bAbI任务，我们发现HyP-MN明显优于MN，获得12％的整体准确性收益。进一步分析表明，MN未能完全推荐任何相关的餐厅，而HyP-MN建议80％的时间里最好的下一家餐厅。

##### URL
[http://arxiv.org/abs/1805.01216](http://arxiv.org/abs/1805.01216)

##### PDF
[http://arxiv.org/pdf/1805.01216](http://arxiv.org/pdf/1805.01216)

