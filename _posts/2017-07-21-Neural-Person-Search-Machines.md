---
layout: post
title: "Neural Person Search Machines"
date: 2017-07-21 07:11:51
categories: arXiv_CV
tags: arXiv_CV Attention
author: Hao Liu, Jiashi Feng, Zequn Jie, Karlekar Jayashree, Bo Zhao, Meibin Qi, Jianguo Jiang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of person search in the wild in this work. Instead of comparing the query against all candidate regions generated in a query-blind manner, we propose to recursively shrink the search area from the whole image till achieving precise localization of the target person, by fully exploiting information from the query and contextual cues in every recursive search step. We develop the Neural Person Search Machines (NPSM) to implement such recursive localization for person search. Benefiting from its neural search mechanism, NPSM is able to selectively shrink its focus from a loose region to a tighter one containing the target automatically. In this process, NPSM employs an internal primitive memory component to memorize the query representation which modulates the attention and augments its robustness to other distracting regions. Evaluations on two benchmark datasets, CUHK-SYSU Person Search dataset and PRW dataset, have demonstrated that our method can outperform current state-of-the-arts in both mAP and top-1 evaluation protocols.

##### Abstract (translated by Google)
我们调查了这项工作在野外搜索人的问题。我们不是将查询与以查询盲方式生成的所有候选区域进行比较，而是从整个图像中递归地缩小搜索区域，直到实现目标人的精确定位，通过充分利用查询中的信息和每个递归搜索步骤。我们开发神经人搜索机器（NPSM）来实现人类搜索的这种递归本地化。受益于它的神经搜索机制，NPSM能够选择性地将其焦点从松散的区域缩小到包含目标的更紧密的区域。在这个过程中，NPSM使用内部原始存储器组件来记忆查询表示，该查询表示调节注意力，并增强其对其他分心区域的鲁棒性。对两个基准数据集（CUHK-SYSU Person Search数据集和PRW数据集）的评估表明，我们的方法在mAP和top-1评估协议中都可以胜过当前的最新技术。

##### URL
[https://arxiv.org/abs/1707.06777](https://arxiv.org/abs/1707.06777)

##### PDF
[https://arxiv.org/pdf/1707.06777](https://arxiv.org/pdf/1707.06777)

