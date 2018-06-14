---
layout: post
title: "Unsupervised Detection of Lesions in Brain MRI using constrained adversarial auto-encoders"
date: 2018-06-13 12:15:54
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection
author: Xiaoran Chen, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Lesion detection in brain Magnetic Resonance Images (MRI) remains a challenging task. State-of-the-art approaches are mostly based on supervised learning making use of large annotated datasets. Human beings, on the other hand, even non-experts, can detect most abnormal lesions after seeing a handful of healthy brain images. Replicating this capability of using prior information on the appearance of healthy brain structure to detect lesions can help computers achieve human level abnormality detection, specifically reducing the need for numerous labeled examples and bettering generalization of previously unseen lesions. To this end, we study detection of lesion regions in an unsupervised manner by learning data distribution of brain MRI of healthy subjects using auto-encoder based methods. We hypothesize that one of the main limitations of the current models is the lack of consistency in latent representation. We propose a simple yet effective constraint that helps mapping of an image bearing lesion close to its corresponding healthy image in the latent space. We use the Human Connectome Project dataset to learn distribution of healthy-appearing brain MRI and report improved detection, in terms of AUC, of the lesions in the BRATS challenge dataset.

##### Abstract (translated by Google)
脑部磁共振图像（MRI）中的病变检测仍然是一项具有挑战性的任务。最先进的方法主要基于监督式学习，利用大型注释数据集。另一方面，即使是非专家，人类在看到一些健康的大脑图像后也能发现大部分异常病变。复制这种使用关于健康大脑结构出现的先前信息来检测病变的能力可以帮助计算机实现人体水平异常检测，特别是减少了对大量标记示例的需求，并且改善了先前未见病变的泛化。为此，我们通过使用基于自动编码器的方法学习健康受试者的脑MRI的数据分布来以无监督方式研究病变区域的检测。我们假设当前模型的一个主要局限是潜在表示缺乏一致性。我们提出了一种简单而有效的约束，有助于在潜在空间中映射带有图像的病灶接近其对应的健康图像。我们使用Human Connectome Project数据集来学习健康出现的大脑MRI的分布，并报告改善的BRATS质疑数据集中病变的AUC检测。

##### URL
[http://arxiv.org/abs/1806.04972](http://arxiv.org/abs/1806.04972)

##### PDF
[http://arxiv.org/pdf/1806.04972](http://arxiv.org/pdf/1806.04972)

