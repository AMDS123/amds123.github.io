---
layout: post
title: "FAQ-based Question Answering via Word Alignment"
date: 2015-07-09 18:11:03
categories: arXiv_CL
tags: arXiv_CL Sparse
author: Zhiguo Wang, Abraham Ittycheriah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel word-alignment-based method to solve the FAQ-based question answering task. First, we employ a neural network model to calculate question similarity, where the word alignment between two questions is used for extracting features. Second, we design a bootstrap-based feature extraction method to extract a small set of effective lexical features. Third, we propose a learning-to-rank algorithm to train parameters more suitable for the ranking tasks. Experimental results, conducted on three languages (English, Spanish and Japanese), demonstrate that the question similarity model is more effective than baseline systems, the sparse features bring 5% improvements on top-1 accuracy, and the learning-to-rank algorithm works significantly better than the traditional method. We further evaluate our method on the answer sentence selection task. Our method outperforms all the previous systems on the standard TREC data set.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于字对齐的方法来解决基于FAQ的问题回答任务。首先，我们使用神经网络模型来计算问题相似度，其中使用两个问题之间的词对齐来提取特征。其次，我们设计了一个基于bootstrap的特征提取方法来提取一小组有效的词汇特征。第三，我们提出了一个学习到排序算法来训练更适合排序任务的参数。在三种语言（英语，西班牙语和日语）上进行的实验结果表明，问题相似度模型比基准系统更有效，稀疏特征对top-1准确性带来5％的改进，并且学习到排序算法明显优于传统方法。我们在回答句子选择任务上进一步评估我们的方法。我们的方法胜过了标准TREC数据集上的所有以前的系统。

##### URL
[https://arxiv.org/abs/1507.02628](https://arxiv.org/abs/1507.02628)

##### PDF
[https://arxiv.org/pdf/1507.02628](https://arxiv.org/pdf/1507.02628)

