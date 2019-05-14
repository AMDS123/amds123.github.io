---
layout: post
title: "High Performance Visual Tracking with Circular and Structural Operators"
date: 2018-10-13 07:06:14
categories: arXiv_AI
tags: arXiv_AI Tracking Optimization Relation
author: Peng Gao, Yipeng Ma, Ke Song, Chao Li, Fei Wang, Liyi Xiao, Yan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a novel circular and structural operator tracker (CSOT) is proposed for high performance visual tracking, it not only possesses the powerful discriminative capability of SOSVM but also efficiently inherits the superior computational efficiency of DCF. Based on the proposed circular and structural operators, a set of primal confidence score maps can be obtained by circular correlating feature maps with their corresponding structural correlation filters. Furthermore, an implicit interpolation is applied to convert the multi-resolution feature maps to the continuous domain and make all primal confidence score maps have the same spatial resolution. Then, we exploit an efficient ensemble post-processor based on relative entropy, which can coalesce primal confidence score maps and create an optimal confidence score map for more accurate localization. The target is localized on the peak of the optimal confidence score map. Besides, we introduce a collaborative optimization strategy to update circular and structural operators by iteratively training structural correlation filters, which significantly reduces computational complexity and improves robustness. Experimental results demonstrate that our approach achieves state-of-the-art performance in mean AUC scores of 71.5% and 69.4% on the OTB-2013 and OTB-2015 benchmarks respectively, and obtains a third-best expected average overlap (EAO) score of 29.8% on the VOT-2017 benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.08208](http://arxiv.org/abs/1804.08208)

##### PDF
[http://arxiv.org/pdf/1804.08208](http://arxiv.org/pdf/1804.08208)

