---
layout: post
title: "What Synthesis is Missing: Depth Adaptation Integrated with Weak Supervision for Indoor Scene Parsing"
date: 2019-03-23 08:26:34
categories: arXiv_CV
tags: arXiv_CV Salient Weakly_Supervised Transfer_Learning Deep_Learning
author: Keng-Chi Liu, Yi-Ting Shen, Jan P. Klopp, Liang-Gee Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Scene Parsing is a crucial step to enable autonomous systems to understand and interact with their surroundings. Supervised deep learning methods have made great progress in solving scene parsing problems, however, come at the cost of laborious manual pixel-level annotation. To alleviate this effort synthetic data as well as weak supervision have both been investigated. Nonetheless, synthetically generated data still suffers from severe domain shift while weak labels are often imprecise. Moreover, most existing works for weakly supervised scene parsing are limited to salient foreground objects. The aim of this work is hence twofold: Exploit synthetic data where feasible and integrate weak supervision where necessary. More concretely, we address this goal by utilizing depth as transfer domain because its synthetic-to-real discrepancy is much lower than for color. At the same time, we perform weak localization from easily obtainable image level labels and integrate both using a novel contour-based scheme. Our approach is implemented as a teacher-student learning framework to solve the transfer learning problem by generating a pseudo ground truth. Using only depth-based adaptation, this approach already outperforms previous transfer learning approaches on the popular indoor scene parsing SUN RGB-D dataset. Our proposed two-stage integration more than halves the gap towards fully supervised methods when compared to previous state-of-the-art in transfer learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09781](http://arxiv.org/abs/1903.09781)

##### PDF
[http://arxiv.org/pdf/1903.09781](http://arxiv.org/pdf/1903.09781)

