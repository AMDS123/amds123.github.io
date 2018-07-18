---
layout: post
title: "Bench-Marking Information Extraction in Semi-Structured Historical Handwritten Records"
date: 2018-07-17 08:13:19
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Animesh Prasad, Herv&#xe9; D&#xe9;jean, Jean-Luc Meunier, Max Weidemann, Johannes Michael, Gundram Leifert
mathjax: true
---

* content
{:toc}

##### Abstract
In this report, we present our findings from benchmarking experiments for information extraction on historical handwritten marriage records Esposalles from IEHHR - ICDAR 2017 robust reading competition. The information extraction is modeled as semantic labeling of the sequence across 2 set of labels. This can be achieved by sequentially or jointly applying handwritten text recognition (HTR) and named entity recognition (NER). We deploy a pipeline approach where first we use state-of-the-art HTR and use its output as input for NER. We show that given low resource setup and simple structure of the records, high performance of HTR ensures overall high performance. We explore the various configurations of conditional random fields and neural networks to benchmark NER on given certain noisy input. The best model on 10-fold cross-validation as well as blind test data uses n-gram features with bidirectional long short-term memory.

##### Abstract (translated by Google)
在本报告中，我们通过IEHHR的历史手写婚姻记录Esposalles的信息提取基准测试实验我们的研究结果 -  ICDAR 2017强大的阅读竞赛。信息提取被建模为跨两组标签的序列的语义标记。这可以通过顺序或联合应用手写文本识别（HTR）和命名实体识别（NER）来实现。我们部署了一种管道方法，首先我们使用最先进的HTR并将其输出用作NER的输入。我们表明，由于资源设置较少且记录结构简单，HTR的高性能可确保整体高性能。我们探索条件随机场和神经网络的各种配置，以在给定某些噪声输入的情况下对NER进行基准测试。 10倍交叉验证的最佳模型以及盲测数据使用具有双向长短期记忆的n-gram特征。

##### URL
[http://arxiv.org/abs/1807.06270](http://arxiv.org/abs/1807.06270)

##### PDF
[http://arxiv.org/pdf/1807.06270](http://arxiv.org/pdf/1807.06270)

