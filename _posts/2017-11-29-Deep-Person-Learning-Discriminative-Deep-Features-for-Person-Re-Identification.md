---
layout: post
title: "Deep-Person: Learning Discriminative Deep Features for Person Re-Identification"
date: 2017-11-29 03:15:07
categories: arXiv_CV
tags: arXiv_CV RNN
author: Xiang Bai, Mingkun Yang, Tengteng Huang, Zhiyong Dou, Rui Yu, Yongchao Xu
---

* content
{:toc}

##### Abstract
Recently, many methods of person re-identification (Re-ID) rely on part-based feature representation to learn a discriminative pedestrian descriptor. However, the spatial context between these parts is ignored for the independent extractor to each separate part. In this paper, we propose to apply Long Short-Term Memory (LSTM) in an end-to-end way to model the pedestrian, seen as a sequence of body parts from head to foot. Integrating the contextual information strengthens the discriminative ability of local representation. We also leverage the complementary information between local and global feature. Furthermore, we integrate both identification task and ranking task in one network, where a discriminative embedding and a similarity measurement are learned concurrently. This results in a novel three-branch framework named Deep-Person, which learns highly discriminative features for person Re-ID. Experimental results demonstrate that Deep-Person outperforms the state-of-the-art methods by a large margin on three challenging datasets including Market-1501, CUHK03, and DukeMTMC-reID. Specifically, combining with a re-ranking approach, we achieve a 90.84% mAP on Market-1501 under single query setting.

##### Abstract (translated by Google)
最近，人们重新识别（Re-ID）的许多方法依赖于基于部分的特征表示来学习有区别的行人描述符。然而，这些部分之间的空间上下文被忽略了独立的提取器到每个单独的部分。在本文中，我们建议以端到端的方式应用长时间短记忆（LSTM）来对行人进行建模，从头到脚看作是一系列身体部位。整合上下文信息增强了当地代表性的区别能力。我们还利用本地和全球功能之间的互补信息。此外，我们将识别任务和排序任务都集成在一个网络中，同时学习判别嵌入和相似性度量。这导致了一个名为Deep-Person的新型三分支框架，该框架学习人Re-ID的高判别性特征。实验结果表明，Deep-Person在三个具有挑战性的数据集（包括Market-1501，CUHK03和DukeMMC-reID）上大大优于最先进的方法。具体而言，结合重新排序的方法，在单一查询设置下，我们在Market-1501上实现了90.84％的mAP。

##### URL
[https://arxiv.org/abs/1711.10658](https://arxiv.org/abs/1711.10658)

