---
layout: post
title: "SemRe-Rank: Improving Automatic Term Extraction By Incorporating Semantic Relatedness With Personalised PageRank"
date: 2018-03-28 20:52:19
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding
author: Ziqi Zhang, Jie Gao, Fabio Ciravegna
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic Term Extraction deals with the extraction of terminology from a domain specific corpus, and has long been an established research area in data and knowledge acquisition. ATE remains a challenging task as it is known that there is no existing ATE methods that can consistently outperform others in any domain. This work adopts a refreshed perspective to this problem: instead of searching for such a 'one-size-fit-all' solution that may never exist, we propose to develop generic methods to 'enhance' existing ATE methods. We introduce SemRe-Rank, the first method based on this principle, to incorporate semantic relatedness - an often overlooked venue - into an existing ATE method to further improve its performance. SemRe-Rank incorporates word embeddings into a personalised PageRank process to compute 'semantic importance' scores for candidate terms from a graph of semantically related words (nodes), which are then used to revise the scores of candidate terms computed by a base ATE algorithm. Extensively evaluated with 13 state-of-the-art base ATE methods on four datasets of diverse nature, it is shown to have achieved widespread improvement over all base methods and across all datasets, with up to 15 percentage points when measured by the Precision in the top ranked K candidate terms (the average for a set of K's), or up to 28 percentage points in F1 measured at a K that equals to the expected real terms in the candidates (F1 in short). Compared to an alternative approach built on the well-known TextRank algorithm, SemRe-Rank can potentially outperform by up to 8 points in Precision at top K, or up to 17 points in F1.

##### Abstract (translated by Google)
自动术语提取涉及从领域特定语料库中提取术语，并且一直以来都是数据和知识获取领域的一个既定研究领域。 ATE仍然是一项具有挑战性的任务，因为众所周知，目前没有任何ATE方法可以在任何领域持续超越其他方法。这项工作对这个问题采取了更新的观点：我们不是寻找可能永远不会存在的“一种尺寸适合所有”解决方案，而是开发通用方法来“增强”现有的ATE方法。我们引入基于这一原理的第一种方法SemRe-Rank，将语义相关性（一个经常被忽视的场所）纳入现有的ATE方法中，以进一步提高其性能。 SemRe-Rank将单词嵌入合并到个性化的PageRank过程中，以根据语义相关词（节点）的图计算候选词的“语义重要性”分数，然后将其用于修改由基本ATE算法计算的候选词的分数。在四种不同性质的数据集上用13种最先进的基本ATE方法进行了广泛的评估，结果表明它已经在所有基本方法和所有数据集上得到了广泛的改进，在精度测量时达到了15个百分点排名靠前的K个候选词（一组K的平均数），或者在等于候选人期望实际词（简称F1）的K中测量的F1中高达28个百分点。与使用众所周知的TextRank算法构建的替代方法相比，SemRe-Rank可能在顶级K中的精度可能高出8个点，或者在F1中高达17点。

##### URL
[http://arxiv.org/abs/1711.03373](http://arxiv.org/abs/1711.03373)

##### PDF
[http://arxiv.org/pdf/1711.03373](http://arxiv.org/pdf/1711.03373)

