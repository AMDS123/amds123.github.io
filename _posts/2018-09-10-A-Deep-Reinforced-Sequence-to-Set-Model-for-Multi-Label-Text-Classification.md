---
layout: post
title: "A Deep Reinforced Sequence-to-Set Model for Multi-Label Text Classification"
date: 2018-09-10 03:33:48
categories: arXiv_CL
tags: arXiv_CL Text_Classification Reinforcement_Learning Classification Relation
author: Pengcheng Yang, Shuming Ma, Yi Zhang, Junyang Lin, Qi Su, Xu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label text classification (MLTC) aims to assign multiple labels to each sample in the dataset. The labels usually have internal correlations. However, traditional methods tend to ignore the correlations between labels. In order to capture the correlations between labels, the sequence-to-sequence (Seq2Seq) model views the MLTC task as a sequence generation problem, which achieves excellent performance on this task. However, the Seq2Seq model is not suitable for the MLTC task in essence. The reason is that it requires humans to predefine the order of the output labels, while some of the output labels in the MLTC task are essentially an unordered set rather than an ordered sequence. This conflicts with the strict requirement of the Seq2Seq model for the label order. In this paper, we propose a novel sequence-to-set framework utilizing deep reinforcement learning, which not only captures the correlations between labels, but also reduces the dependence on the label order. Extensive experimental results show that our proposed method outperforms the competitive baselines by a large margin.

##### Abstract (translated by Google)
多标签文本分类（MLTC）旨在为数据集中的每个样本分配多个标签。标签通常具有内部关联。然而，传统方法倾向于忽略标签之间的相关性。为了捕获标签之间的相关性，序列到序列（Seq2Seq）模型将MLTC任务视为序列生成问题，这在该任务上实现了优异的性能。但是，Seq2Seq模型本质上不适合MLTC任务。原因是它需要人类预定义输出标签的顺序，而MLTC任务中的一些输出标签基本上是无序集合而不是有序序列。这与Seq2Seq模型对标签顺序的严格要求相冲突。在本文中，我们提出了一种利用深度强化学习的新型序列到集合框架，它不仅捕获标签之间的相关性，还减少了对标签顺序的依赖性。大量实验结果表明，我们提出的方法大大超过了竞争基线。

##### URL
[http://arxiv.org/abs/1809.03118](http://arxiv.org/abs/1809.03118)

##### PDF
[http://arxiv.org/pdf/1809.03118](http://arxiv.org/pdf/1809.03118)

