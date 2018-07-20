---
layout: post
title: "High Performance Visual Tracking with Circular and Structural Operators"
date: 2018-07-19 08:34:03
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Relation
author: Peng Gao, Yipeng Ma, Fei Wang, Ke Song, Chao Li, Yan Zhang, Liyi Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a novel circular and structural operator tracker (CSOT) is proposed for high performance visual tracking, it not only possesses the powerful discriminative capability of SOSVM but also efficiently inherits the superior computational efficiency of DCF. Based on the proposed circular and structural operators, a set of primal confidence score maps can be obtained by circular correlating feature maps with their corresponding structural correlation filters. Furthermore, an implicit interpolation is applied to convert the multi-resolution feature maps to the continuous domain and make all primal confidence score maps have the same spatial resolution. Then, we exploit an efficient ensemble post-processor based on relative entropy, which can coalesce primal confidence score maps and create an optimal confidence score map for more accurate localization. The target is localized on the peak of the optimal confidence score map. Besides, we introduce a collaborative optimization strategy to update circular and structural operators by iteratively training structural correlation filters, which significantly reduces computational complexity and improves robustness. Experimental results demonstrate that our approach achieves state-of-the-art performance in mean AUC scores of 71.5% and 69.4% on the OTB-2013 and OTB-2015 benchmarks respectively, and obtains a third-best expected average overlap (EAO) score of 29.8% on the VOT-2017 benchmark.

##### Abstract (translated by Google)
本文提出了一种新颖的圆形和结构操作跟踪器（CSOT），用于高性能视觉跟踪，它不仅具有SOSVM强大的判别能力，而且有效地继承了DCF的优越计算效率。基于所提出的循环和结构算子，可以通过将特征映射与其对应的结构相关滤波器进行循环相关来获得一组原始置信度得分图。此外，应用隐式插值将多分辨率特征映射转换为连续域，并使所有原始置信度得分图具有相同的空间分辨率。然后，我们利用基于相对熵的有效集合后处理器，其可以合并原始置信度得分图并创建最佳置信度得分图以用于更准确的定位。目标位于最佳置信度得分图的峰值上。此外，我们引入协作优化策略，通过迭代训练结构相关滤波器来更新循环和结构运算符，从而显着降低计算复杂度并提高鲁棒性。实验结果表明，我们的方法分别在OTB-2013和OTB-2015基准测试中获得了71.5％和69.4％的平均AUC分数的最新表现，并获得了第三最佳预期平均重叠（EAO）分数在VOT-2017基准测试中占29.8％。

##### URL
[http://arxiv.org/abs/1804.08208](http://arxiv.org/abs/1804.08208)

##### PDF
[http://arxiv.org/pdf/1804.08208](http://arxiv.org/pdf/1804.08208)

