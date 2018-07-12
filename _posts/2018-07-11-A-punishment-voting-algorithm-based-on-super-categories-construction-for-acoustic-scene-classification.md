---
layout: post
title: "A punishment voting algorithm based on super categories construction for acoustic scene classification"
date: 2018-07-11 11:14:19
categories: arXiv_SD
tags: arXiv_SD Classification
author: Weiping Zheng, Zhenyao Mo, Jiantao Yi
mathjax: true
---

* content
{:toc}

##### Abstract
In acoustic scene classification researches, audio segment is usually split into multiple samples. Majority voting is then utilized to ensemble the results of the samples. In this paper, we propose a punishment voting algorithm based on the super categories construction method for acoustic scene classification. Specifically, we propose a DenseNet-like model as the base classifier. The base classifier is trained by the CQT spectrograms generated from the raw audio segments. Taking advantage of the results of the base classifier, we propose a super categories construction method using the spectral clustering. Super classifiers corresponding to the constructed super categories are further trained. Finally, the super classifiers are utilized to enhance the majority voting of the base classifier by punishment voting. Experiments show that the punishment voting obviously improves the performances on both the DCASE2017 Development dataset and the LITIS Rouen dataset.

##### Abstract (translated by Google)
在声学场景分类研究中，音频片段通常被分成多个样本。然后利用多数投票来整合样本的结果。在本文中，我们提出了一种基于声类场景分类的超类别构造方法的惩罚投票算法。具体来说，我们提出了一个类似DenseNet的模型作为基本分类器。基本分类器由从原始音频段生成的CQT频谱图训练。利用基分类器的结果，我们提出了一种使用谱聚类的超类别构造方法。对应于构建的超类别的超级分类器被进一步训练。最后，超级分类器用于通过惩罚投票来增强基本分类器的多数表决。实验表明，惩罚投票显着提高了DCASE2017开发数据集和LITIS Rouen数据集的性能。

##### URL
[http://arxiv.org/abs/1807.04073](http://arxiv.org/abs/1807.04073)

##### PDF
[http://arxiv.org/pdf/1807.04073](http://arxiv.org/pdf/1807.04073)

