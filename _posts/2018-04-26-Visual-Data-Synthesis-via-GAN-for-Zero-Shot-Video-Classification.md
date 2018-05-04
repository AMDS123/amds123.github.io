---
layout: post
title: "Visual Data Synthesis via GAN for Zero-Shot Video Classification"
date: 2018-04-26 14:10:41
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Video_Classification Inference Classification Relation
author: Chenrui Zhang, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Learning (ZSL) in video classification is a promising research direction, which aims to tackle the challenge from explosive growth of video categories. Most existing methods exploit seen-to-unseen correlation via learning a projection between visual and semantic spaces. However, such projection-based paradigms cannot fully utilize the discriminative information implied in data distribution, and commonly suffer from the information degradation issue caused by "heterogeneity gap". In this paper, we propose a visual data synthesis framework via GAN to address these problems. Specifically, both semantic knowledge and visual distribution are leveraged to synthesize video feature of unseen categories, and ZSL can be turned into typical supervised problem with the synthetic features. First, we propose multi-level semantic inference to boost video feature synthesis, which captures the discriminative information implied in joint visual-semantic distribution via feature-level and label-level semantic inference. Second, we propose Matching-aware Mutual Information Correlation to overcome information degradation issue, which captures seen-to-unseen correlation in matched and mismatched visual-semantic pairs by mutual information, providing the zero-shot synthesis procedure with robust guidance signals. Experimental results on four video datasets demonstrate that our approach can improve the zero-shot video classification performance significantly.

##### Abstract (translated by Google)
视频分类中的零点学习（ZSL）是一个有前途的研究方向，旨在应对视频类别爆炸性增长带来的挑战。大多数现有的方法通过学习视觉和语义空间之间的投影来利用看不见的相关性。然而，这种基于投影的范式不能充分利用数据分布中隐含的区分信息，而且常常遭受由“异质性差距”引起的信息退化问题。在本文中，我们通过GAN提出了一个可视化数据合成框架来解决这些问题。具体而言，利用语义知识和视觉分布来合成未见类别的视频特征，并将ZSL转化为具有综合特征的典型监督问题。首先，我们提出了多层次的语义推理来促进视频特征合成，通过特征层次和标签层次语义推断来捕获联合视觉语义分布所蕴含的判别信息。其次，我们提出匹配感知互信息相关来克服信息降级问题，该问题通过互信息捕获匹配和不匹配视觉语义对中的看不见的相关性，为零炮合成过程提供鲁棒的引导信号。在四个视频数据集上的实验结果表明，我们的方法可以显着提高零镜头视频分类性能。

##### URL
[https://arxiv.org/abs/1804.10073](https://arxiv.org/abs/1804.10073)

##### PDF
[https://arxiv.org/pdf/1804.10073](https://arxiv.org/pdf/1804.10073)

