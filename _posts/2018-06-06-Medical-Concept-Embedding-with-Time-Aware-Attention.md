---
layout: post
title: "Medical Concept Embedding with Time-Aware Attention"
date: 2018-06-06 07:45:06
categories: arXiv_AI
tags: arXiv_AI Attention Embedding Relation
author: Xiangrui Cai, Jinyang Gao, Kee Yuan Ngiam, Beng Chin Ooi, Ying Zhang, Xiaojie Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Embeddings of medical concepts such as medication, procedure and diagnosis codes in Electronic Medical Records (EMRs) are central to healthcare analytics. Previous work on medical concept embedding takes medical concepts and EMRs as words and documents respectively. Nevertheless, such models miss out the temporal nature of EMR data. On the one hand, two consecutive medical concepts do not indicate they are temporally close, but the correlations between them can be revealed by the time gap. On the other hand, the temporal scopes of medical concepts often vary greatly (e.g., \textit{common cold} and \textit{diabetes}). In this paper, we propose to incorporate the temporal information to embed medical codes. Based on the Continuous Bag-of-Words model, we employ the attention mechanism to learn a "soft" time-aware context window for each medical concept. Experiments on public and proprietary datasets through clustering and nearest neighbour search tasks demonstrate the effectiveness of our model, showing that it outperforms five state-of-the-art baselines.

##### Abstract (translated by Google)
电子医疗记录（EMR）中的药物，程序和诊断代码等医疗概念的嵌入是医疗保健分析的核心。以前关于医学概念嵌入的研究分别将医学概念和电子病历作为单词和文档。尽管如此，这些模型错过了EMR数据的时间性质。一方面，两个连续的医学概念并不表示它们在时间上接近，但它们之间的相关性可以通过时间间隙显现出来。另一方面，医学概念的时间范围经常变化很大（例如，\ textit {普通感冒}和\ textit {糖尿病}）。在本文中，我们建议整合时间信息来嵌入医疗代码。基于连续词袋模型，我们采用注意机制为每个医学概念学习“软”时间感知上下文窗口。通过聚类和最近邻搜索任务对公共数据集和专有数据集进行的实验证明了我们模型的有效性，表明它优于五个最先进的基线。

##### URL
[http://arxiv.org/abs/1806.02873](http://arxiv.org/abs/1806.02873)

##### PDF
[http://arxiv.org/pdf/1806.02873](http://arxiv.org/pdf/1806.02873)

