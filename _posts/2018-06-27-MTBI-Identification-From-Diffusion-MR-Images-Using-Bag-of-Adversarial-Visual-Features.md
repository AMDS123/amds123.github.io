---
layout: post
title: "MTBI Identification From Diffusion MR Images Using Bag of Adversarial Visual Features"
date: 2018-06-27 11:41:34
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification
author: Shervin Minaee, Yao Wang, Alp Aygar, Sohae Chung, Xiuyuan Wang, Yvonne W. Lui, Els Fieremans, Steven Flanagan, Joseph Rath
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose bag of adversarial features (BAF) for identifying mild traumatic brain injury (MTBI) patients from their diffusion magnetic resonance images (MRI) (obtained within one month of injury) by incorporating unsupervised feature learning techniques. MTBI is a growing public health problem with an estimated incidence of over 1.7 million people annually in US. Diagnosis is based on clinical history and symptoms, and accurate, concrete measures of injury are lacking. Unlike most of previous works, which use hand-crafted features extracted from different parts of brain for MTBI classification, we employ feature learning algorithms to learn more discriminative representation for this task. A major challenge in this field thus far is the relatively small number of subjects available for training. This makes it difficult to use an end-to-end convolutional neural network to directly classify a subject from MR images. To overcome this challenge, we first apply an adversarial auto-encoder (with convolutional structure) to learn patch-level features, from overlapping image patches extracted from different brain regions. We then aggregate these features through a bag-of-word approach. We perform an extensive experimental study on a dataset of 227 subjects (including 109 MTBI patients, and 118 age and sex matched healthy controls), and compare the bag-of-deep-features with several previous approaches. Our experimental results show that the BAF significantly outperforms earlier works relying on the mean values of MR metrics in selected brain regions.

##### Abstract (translated by Google)
在这项工作中，我们通过引入无监督特征学习技术，提出了一系列用于从其弥散磁共振图像（MRI）（在受伤一个月内获得）中识别轻度创伤性脑损伤（MTBI）患者的敌对特征（BAF）。 MTBI是一个日益严重的公共卫生问题，估计美国每年有超过170万人患病。诊断依据临床病史和症状，缺乏准确，具体的损伤措施。与大多数以前使用从大脑不同部位提取的手工特征进行MTBI分类的作品不同，我们使用特征学习算法来学习更多区分性表示来完成此任务。迄今为止，这一领域的主要挑战是可供培训的科目相对较少。这使得难以使用端到端卷积神经网络来从MR图像直接分类对象。为了克服这个挑战，我们首先应用对抗自动编码器（具有卷积结构）来学习从不同大脑区域提取的重叠图像补丁的补丁级特征。然后，我们通过一袋一袋的方式来汇总这些功能。我们对227名受试者（包括109名MTBI患者和118名年龄和性别匹配的健康对照者）的数据集进行了广泛的实验研究，并将深度特征与以前的几种方法进行了比较。我们的实验结果显示BAF显着优于早期依赖于选定脑区MR指标平均值的作品。

##### URL
[http://arxiv.org/abs/1806.10419](http://arxiv.org/abs/1806.10419)

##### PDF
[http://arxiv.org/pdf/1806.10419](http://arxiv.org/pdf/1806.10419)

