---
layout: post
title: "Unified Neural Architecture for Drug, Disease and Clinical Entity Recognition"
date: 2017-08-11 06:30:23
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Recognition
author: Sunil Kumar Sahu, Ashish Anand
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing methods for biomedical entity recognition task rely on explicit feature engineering where many features either are specific to a particular task or depends on output of other existing NLP tools. Neural architectures have been shown across various domains that efforts for explicit feature design can be reduced. In this work we propose an unified framework using bi-directional long short term memory network (BLSTM) for named entity recognition (NER) tasks in biomedical and clinical domains. Three important characteristics of the framework are as follows - (1) model learns contextual as well as morphological features using two different BLSTM in hierarchy, (2) model uses first order linear conditional random field (CRF) in its output layer in cascade of BLSTM to infer label or tag sequence, (3) model does not use any domain specific features or dictionary, i.e., in another words, same set of features are used in the three NER tasks, namely, disease name recognition (Disease NER), drug name recognition (Drug NER) and clinical entity recognition (Clinical NER). We compare performance of the proposed model with existing state-of-the-art models on the standard benchmark datasets of the three tasks. We show empirically that the proposed framework outperforms all existing models. Further our analysis of CRF layer and word-embedding obtained using character based embedding show their importance.

##### Abstract (translated by Google)
大多数现有的生物医学实体识别任务的方法依赖于明确的特征工程，其中许多特征或者特定于特定的任务，或者依赖于其他现有的NLP工具的输出。已经在各个领域展示了神经架构，可以减少显式特征设计的努力。在这项工作中，我们提出了一个统一的框架，使用双向长期短期记忆网络（BLSTM）命名实体识别（NER）任务在生物医学和临床领域。框架的三个重要特征如下：（1）使用两个不同的层次结构BLSTM模型学习上下文和形态特征;（2）模型使用BLSTM级联中的输出层的一阶线性条件随机场（CRF）推断标签或标签序列;（3）模型不使用任何领域特定的特征或词典，即换句话说，在三个NER任务中使用同一组特征，即疾病名称识别（NER），药物名称识别（Drug NER）和临床实体识别（Clinical NER）。我们将所提出的模型的性能与三个任务的标准基准数据集上现有的最新模型进行比较。我们经验地表明，提出的框架胜过所有现有的模型。进一步分析CRF层和使用基于字符的嵌入获得的字嵌入显示它们的重要性。

##### URL
[https://arxiv.org/abs/1708.03447](https://arxiv.org/abs/1708.03447)

##### PDF
[https://arxiv.org/pdf/1708.03447](https://arxiv.org/pdf/1708.03447)

