---
layout: post
title: "Reinforcement Learning Based Graph-to-Sequence Model for Natural Question Generation"
date: 2019-08-14 03:40:04
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Yu Chen, Lingfei Wu, Mohammed J. Zaki
mathjax: true
---

* content
{:toc}

##### Abstract
Natural question generation (QG) is a challenging yet rewarding task, that aims to generate questions given an input passage and a target answer. Previous works on QG, however, either (i) ignore the rich structure information hidden in the word sequence, (ii) fail to fully exploit the target answer, or (iii) solely rely on cross-entropy loss that leads to issues like exposure bias and evaluation discrepancy between training and testing. To address the above limitations, in this paper, we propose a reinforcement learning (RL) based graph-to-sequence (Graph2Seq) architecture for the QG task. Our model consists of a Graph2Seq generator where a novel bidirectional graph neural network (GNN) based encoder is applied to embed the input passage incorporating the answer information via a simple yet effective Deep Alignment Network, and an evaluator where a mixed objective function combining both cross-entropy loss and RL loss is designed for ensuring the generation of semantically and syntactically valid text. The proposed model is end-to-end trainable, and achieves new state-of-the-art scores and outperforms all previous methods by a great margin on the SQuAD benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04942](http://arxiv.org/abs/1908.04942)

##### PDF
[http://arxiv.org/pdf/1908.04942](http://arxiv.org/pdf/1908.04942)

