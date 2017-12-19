---
layout: post
title: "A General Multi-Graph Matching Approach via Graduated Consistency-regularized Boosting"
date: 2015-02-20 11:45:25
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Junchi Yan, Minsu Cho, Hongyuan Zha, Xiaokang Yang, Stephen Chu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of matching $N$ weighted graphs referring to an identical object or category. More specifically, matching the common node correspondences among graphs. This multi-graph matching problem involves two ingredients affecting the overall accuracy: i) the local pairwise matching affinity score among graphs; ii) the global matching consistency that measures the uniqueness of the pairwise matching results by different chaining orders. Previous studies typically either enforce the matching consistency constraints in the beginning of iterative optimization, which may propagate matching error both over iterations and across graph pairs; or separate affinity optimizing and consistency regularization in two steps. This paper is motivated by the observation that matching consistency can serve as a regularizer in the affinity objective function when the function is biased due to noises or inappropriate modeling. We propose multi-graph matching methods to incorporate the two aspects by boosting the affinity score, meanwhile gradually infusing the consistency as a regularizer. Furthermore, we propose a node-wise consistency/affinity-driven mechanism to elicit the common inlier nodes out of the irrelevant outliers. Extensive results on both synthetic and public image datasets demonstrate the competency of the proposed algorithms.

##### Abstract (translated by Google)
本文讨论了匹配$ N $加权图引用一个相同的对象或类别的问题。更具体地说，匹配图之间的公共节点对应关系。这种多图匹配问题涉及两个因素影响整体的准确性：i）图中的局部成对匹配亲和度得分; ii）全局匹配一致性，其通过不同的链接顺序来度量成对匹配结果的唯一性。先前的研究通常在迭代优化开始时强制执行匹配一致性约束，这可能在迭代和图对之间传播匹配误差;或者在两个步骤中分离亲和力优化和一致性正则化。本文的动机是在函数由于噪声或不适当建模而导致偏差的情况下，匹配一致性可以作为亲和目标函数中的正则化函数。我们提出了多图匹配的方法，通过提高亲和度得分来融合这两个方面，同时逐渐注入一致性作为调整者。此外，我们提出了节点明智的一致性/亲和力驱动机制，从无关的异常值中引出常见的内部节点。在综合和公开的图像数据集上的广泛的结果证明了所提出的算法的能力。

##### URL
[https://arxiv.org/abs/1502.05840](https://arxiv.org/abs/1502.05840)

##### PDF
[https://arxiv.org/pdf/1502.05840](https://arxiv.org/pdf/1502.05840)

