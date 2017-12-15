---
layout: post
title: "Mapping Tractography Across Subjects"
date: 2016-01-29 15:50:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Thien Bao Nguyen, Emanuele Olivetti, Paolo Avesani
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion magnetic resonance imaging (dMRI) and tractography provide means to study the anatomical structures within the white matter of the brain. When studying tractography data across subjects, it is usually necessary to align, i.e. to register, tractographies together. This registration step is most often performed by applying the transformation resulting from the registration of other volumetric images (T1, FA). In contrast with registration methods that "transform" tractographies, in this work, we try to find which streamline in one tractography correspond to which streamline in the other tractography, without any transformation. In other words, we try to find a "mapping" between the tractographies. We propose a graph-based solution for the tractography mapping problem and we explain similarities and differences with the related well-known graph matching problem. Specifically, we define a loss function based on the pairwise streamline distance and reformulate the mapping problem as combinatorial optimization of that loss function. We show preliminary promising results where we compare the proposed method, implemented with simulated annealing, against a standard registration techniques in a task of segmentation of the corticospinal tract.

##### Abstract (translated by Google)
扩散磁共振成像（dMRI）和纤维束成像提供了研究大脑白质内解剖结构的手段。在研究跨主体的纤维束数据时，通常有必要调整，即将纤维束图登记在一起。该注册步骤通常通过应用由其他体积图像（T1，FA）的配准而产生的转换来执行。与“转换”纤维束的注册方法相反，在本文中，我们试图找出哪一种纤维束的流线符合另一种纤维束的流线，而没有任何转换。换句话说，我们试图找到一个迂回路线之间的“映射”。我们提出了一个基于图的解决方案的路由映射问题，我们解释相似之处，与相关的众所周知的图匹配问题的差异。具体而言，我们基于成对的流线距离定义损失函数，并将映射问题重新组合优化为损失函数。我们展示初步有前途的结果，我们比较所提出的方法，实施模拟退火，与标准注册技术在皮质脊髓束分割的任务。

##### URL
[https://arxiv.org/abs/1601.08165](https://arxiv.org/abs/1601.08165)

##### PDF
[https://arxiv.org/pdf/1601.08165](https://arxiv.org/pdf/1601.08165)

