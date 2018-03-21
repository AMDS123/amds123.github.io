---
layout: post
title: "Experiments with Neural Networks for Small and Large Scale Authorship Verification"
date: 2018-03-17 04:11:22
categories: arXiv_CL
tags: arXiv_CL Review Language_Model
author: Marjan Hosseinia, Arjun Mukherjee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose two models for a special case of authorship verification problem. The task is to investigate whether the two documents of a given pair are written by the same author. We consider the authorship verification problem for both small and large scale datasets. The underlying small-scale problem has two main challenges: First, the authors of the documents are unknown to us because no previous writing samples are available. Second, the two documents are short (a few hundred to a few thousand words) and may differ considerably in the genre and/or topic. To solve it we propose transformation encoder to transform one document of the pair into the other. This document transformation generates a loss which is used as a recognizable feature to verify if the authors of the pair are identical. For the large scale problem where various authors are engaged and more examples are available with larger length, a parallel recurrent neural network is proposed. It compares the language models of the two documents. We evaluate our methods on various types of datasets including Authorship Identification datasets of PAN competition, Amazon reviews, and machine learning articles. Experiments show that both methods achieve stable and competitive performance compared to the baselines.

##### Abstract (translated by Google)
我们针对作者身份验证问题的特例提出了两种模型。其任务是调查给定对的两个文档是否由同一个作者编写。我们考虑小型和大型数据集的作者身份验证问题。潜在的小规模问题有两个主要挑战：第一，文件的作者对我们是未知的，因为没有以前的文字样本可用。其次，这两份文件很短（几百到几千字），可能在体裁和/或主题上有很大差异。为了解决这个问题，我们建议使用变换编码器将一对文档转换为另一个文档。此文档转换会产生一个损失，该损失将用作可识别的功能，以验证对的作者是否相同。对于各种作者参与的大规模问题以及更多可用的较大长度的例子，提出了并行循环神经网络。它比较了这两个文件的语言模型。我们评估我们的方法在各种类型的数据集上，包括PAN竞赛的作者身份识别数据集，亚马逊评论和机器学习文章。实验表明，与基线相比，两种方法都实现了稳定且有竞争力的表现。

##### URL
[https://arxiv.org/abs/1803.06456](https://arxiv.org/abs/1803.06456)

##### PDF
[https://arxiv.org/pdf/1803.06456](https://arxiv.org/pdf/1803.06456)

