---
layout: post
title: "Self-Reinforced Cascaded Regression for Face Alignment"
date: 2017-11-23 09:15:22
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Xin Fan, Risheng Liu, Kang Huyan, Yuyao Feng, Zhongxuan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Cascaded regression is prevailing in face alignment thanks to its accuracy and robustness, but typically demands manually annotated examples having low discrepancy between shape-indexed features and shape updates. In this paper, we propose a self-reinforced strategy that iteratively expands the quantity and improves the quality of training examples, thus upgrading the performance of cascaded regression itself. The reinforced term evaluates the example quality upon the consistence on both local appearance and global geometry of human faces, and constitutes the example evolution by the philosophy of "survival of the fittest". We train a set of discriminative classifiers, each associated with one landmark label, to prune those examples with inconsistent local appearance, and further validate the geometric relationship among groups of labeled landmarks against the common global geometry derived from a projective invariant. We embed this generic strategy into typical cascaded regressions, and the alignment results on several benchmark data sets demonstrate its effectiveness to predict good examples starting from a small subset.

##### Abstract (translated by Google)
由于其精确性和鲁棒性，级联回归在面对齐方面占优势，但通常需要手动注释的示例，其形状索引特征和形状更新之间的差异较小。在本文中，我们提出了一种自我强化的策略，迭代地扩大了数量，提高了训练样例的质量，从而提升了级联回归本身的性能。强化术语是以人脸的局部外形和全局几何的一致性来评价示例质量，并以“适者生存”的哲学构成示例演化。我们训练一组区分性的分类器，每个分类器都与一个地标标签相关联，以修剪那些具有不一致局部外观的例子，进一步验证标记地标组之间的几何关系与从投影不变量导出的常见全局几何。我们将这种通用策略嵌入到典型的级联回归中，并且几个基准数据集上的对齐结果证明了从小子集开始预测好例子的有效性。

##### URL
[https://arxiv.org/abs/1711.08624](https://arxiv.org/abs/1711.08624)

##### PDF
[https://arxiv.org/pdf/1711.08624](https://arxiv.org/pdf/1711.08624)

