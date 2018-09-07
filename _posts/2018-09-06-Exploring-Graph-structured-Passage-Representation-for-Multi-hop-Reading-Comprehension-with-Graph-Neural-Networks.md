---
layout: post
title: "Exploring Graph-structured Passage Representation for Multi-hop Reading Comprehension with Graph Neural Networks"
date: 2018-09-06 15:18:14
categories: arXiv_AI
tags: arXiv_AI Attention CNN Inference
author: Linfeng Song, Zhiguo Wang, Mo Yu, Yue Zhang, Radu Florian, Daniel Gildea
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-hop reading comprehension focuses on one type of factoid question, where a system needs to properly integrate multiple pieces of evidence to correctly answer a question. Previous work approximates global evidence with local coreference information, encoding coreference chains with DAG-styled GRU layers within a gated-attention reader. However, coreference is limited in providing information for rich inference. We introduce a new method for better connecting global evidence, which forms more complex graphs compared to DAGs. To perform evidence integration on our graphs, we investigate two recent graph neural networks, namely graph convolutional network (GCN) and graph recurrent network (GRN). Experiments on two standard datasets show that richer global information leads to better answers. Our method performs better than all published results on these datasets.

##### Abstract (translated by Google)
多跳阅读理解侧重于一种类型的事实问题，其中系统需要正确地整合多个证据来正确回答问题。以前的工作使用本地共享信息来近似全局证据，在门控注意力读取器中编码具有DAG样式GRU层的共参考链。但是，共同参与在提供丰富推理的信息方面受到限制。我们引入了一种更好地连接全局证据的新方法，与DAG相比，它形成了更复杂的图形。为了在我们的图上进行证据整合，我们研究了两个最近的图神经网络，即图卷积网络（GCN）和图复现网络（GRN）。对两个标准数据集的实验表明，更丰富的全球信息可以带来更好的答案。我们的方法比这些数据集上的所有已发布结果表现更好。

##### URL
[http://arxiv.org/abs/1809.02040](http://arxiv.org/abs/1809.02040)

##### PDF
[http://arxiv.org/pdf/1809.02040](http://arxiv.org/pdf/1809.02040)

