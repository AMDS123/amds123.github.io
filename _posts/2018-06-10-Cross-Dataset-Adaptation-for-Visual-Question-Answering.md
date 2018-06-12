---
layout: post
title: "Cross-Dataset Adaptation for Visual Question Answering"
date: 2018-06-10 21:06:28
categories: arXiv_CV
tags: arXiv_CV QA Quantitative VQA Recognition
author: Wei-Lun Chao, Hexiang Hu, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of cross-dataset adaptation for visual question answering (Visual QA). Our goal is to train a Visual QA model on a source dataset but apply it to another target one. Analogous to domain adaptation for visual recognition, this setting is appealing when the target dataset does not have a sufficient amount of labeled data to learn an "in-domain" model. The key challenge is that the two datasets are constructed differently, resulting in the cross-dataset mismatch on images, questions, or answers. 
 We overcome this difficulty by proposing a novel domain adaptation algorithm. Our method reduces the difference in statistical distributions by transforming the feature representation of the data in the target dataset. Moreover, it maximizes the likelihood of answering questions (in the target dataset) correctly using the Visual QA model trained on the source dataset. We empirically studied the effectiveness of the proposed approach on adapting among several popular Visual QA datasets. We show that the proposed method improves over baselines where there is no adaptation and several other adaptation methods. We both quantitatively and qualitatively analyze when the adaptation can be mostly effective.

##### Abstract (translated by Google)
我们研究视觉问题回答（Visual QA）的交叉数据集适应问题。我们的目标是在源数据集上训练Visual QA模型，但将其应用于另一个目标数据集。类似于视觉识别的领域适应，当目标数据集没有足够数量的标记数据来学习“域内”模型时，该设置很有吸引力。关键的挑战是两个数据集的构造方式不同，导致交叉数据集在图像，问题或答案上不匹配。
 我们通过提出一种新颖的域自适应算法来克服这个困难。我们的方法通过转换目标数据集中数据的特征表示来减少统计分布的差异。此外，它最大限度地利用在源数据集上训练的Visual QA模型正确回答问题（在目标数据集中）的可能性。我们经验地研究了所提出的方法在几种流行的视觉QA数据集之间的适应性的有效性。我们表明，提出的方法改善了基线没有适应和其他几种适应方法。我们都在数量和质量上分析何时适应最为有效。

##### URL
[http://arxiv.org/abs/1806.03726](http://arxiv.org/abs/1806.03726)

##### PDF
[http://arxiv.org/pdf/1806.03726](http://arxiv.org/pdf/1806.03726)

