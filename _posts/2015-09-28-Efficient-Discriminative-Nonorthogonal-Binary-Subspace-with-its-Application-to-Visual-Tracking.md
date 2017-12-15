---
layout: post
title: "Efficient Discriminative Nonorthogonal Binary Subspace with its Application to Visual Tracking"
date: 2015-09-28 16:27:26
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Inference
author: Ang Li, Feng Tang, Yanwen Guo, Hai Tao
mathjax: true
---

* content
{:toc}

##### Abstract
One of the crucial problems in visual tracking is how the object is represented. Conventional appearance-based trackers are using increasingly more complex features in order to be robust. However, complex representations typically not only require more computation for feature extraction, but also make the state inference complicated. We show that with a careful feature selection scheme, extremely simple yet discriminative features can be used for robust object tracking. The central component of the proposed method is a succinct and discriminative representation of the object using discriminative non-orthogonal binary subspace (DNBS) which is spanned by Haar-like features. The DNBS representation inherits the merits of the original NBS in that it efficiently describes the object. It also incorporates the discriminative information to distinguish foreground from background. However, the problem of finding the DNBS bases from an over-complete dictionary is NP-hard. We propose a greedy algorithm called discriminative optimized orthogonal matching pursuit (D-OOMP) to solve this problem. An iterative formulation named iterative D-OOMP is further developed to drastically reduce the redundant computation between iterations and a hierarchical selection strategy is integrated for reducing the search space of features. The proposed DNBS representation is applied to object tracking through SSD-based template matching. We validate the effectiveness of our method through extensive experiments on challenging videos with comparisons against several state-of-the-art trackers and demonstrate its capability to track objects in clutter and moving background.

##### Abstract (translated by Google)
视觉追踪中的关键问题之一是如何表示对象。传统的基于外观的跟踪器正在使用越来越复杂的功能，以保持健壮。然而，复杂的表示通常不仅需要更多的计算来进行特征提取，而且使得状态推断变得复杂。我们表明，仔细的特征选择方案，极其简单但有区别的特征可以用于强大的对象跟踪。该方法的核心部分是利用Haar-like特征所跨越的判别式非正交二进制子空间（DNBS）对对象进行简洁而有区别的表示。 DNBS表示法继承了原始NBS的优点，因为它有效地描述了对象。它还包含区分信息来区分前景和背景。然而，从一本完整的词典中找到DNBS库的问题是NP难的。为了解决这个问题，我们提出了一种叫做区分优化正交匹配追踪（D-OOMP）的贪婪算法。迭代公式迭代D-OOMP的进一步发展大大减少了迭代之间的冗余计算，集成了层次选择策略来减少特征的搜索空间。所提出的DNBS表示适用于通过基于SSD的模板匹配进行对象跟踪。我们通过对具有挑战性的视频进行大量实验，验证了我们方法的有效性，并与几个最先进的跟踪器进行了比较，并展示了其在杂乱和移动背景下跟踪物体的能力。

##### URL
[https://arxiv.org/abs/1509.08383](https://arxiv.org/abs/1509.08383)

##### PDF
[https://arxiv.org/pdf/1509.08383](https://arxiv.org/pdf/1509.08383)

