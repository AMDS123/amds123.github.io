---
layout: post
title: "Neural Factor Graph Models for Cross-lingual Morphological Tagging"
date: 2018-05-11 19:27:07
categories: arXiv_CL
tags: arXiv_CL Face Relation
author: Chaitanya Malaviya, Matthew R. Gormley, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
Morphological analysis involves predicting the syntactic traits of a word (e.g. {POS: Noun, Case: Acc, Gender: Fem}). Previous work in morphological tagging improves performance for low-resource languages (LRLs) through cross-lingual training with a high-resource language (HRL) from the same family, but is limited by the strict, often false, assumption that tag sets exactly overlap between the HRL and LRL. In this paper we propose a method for cross-lingual morphological tagging that aims to improve information sharing between languages by relaxing this assumption. The proposed model uses factorial conditional random fields with neural network potentials, making it possible to (1) utilize the expressive power of neural network representations to smooth over superficial differences in the surface forms, (2) model pairwise and transitive relationships between tags, and (3) accurately generate tag sets that are unseen or rare in the training data. Experiments on four languages from the Universal Dependencies Treebank demonstrate superior tagging accuracies over existing cross-lingual approaches.

##### Abstract (translated by Google)
形态分析涉及预测单词的句法特征（例如{POS：Noun，Case：Acc，Gender：Fem}）。以前在形态标记方面的工作通过来自同一家族的高资源语言（HRL）进行跨语言培训，从而提高了低资源语言（LRL）的性能，但受限于严格的假设，即假设标签集完全重叠在HRL和LRL之间。在本文中，我们提出了一种跨语言形态标注方法，旨在通过放宽这种假设来改善语言之间的信息共享。所提出的模型使用具有神经网络势的阶乘条件随机场，使得可以（1）利用神经网络表示的表达力来平滑表面形式中的表面差异，（2）模型标签之间的成对和传递关系，以及（3）准确地生成训练数据中看不见或罕见的标签集。来自Universal Dependencies Treebank的四种语言的实验在现有的跨语言方法上表现出卓越的标签精度。

##### URL
[https://arxiv.org/abs/1805.04570](https://arxiv.org/abs/1805.04570)

##### PDF
[https://arxiv.org/pdf/1805.04570](https://arxiv.org/pdf/1805.04570)

