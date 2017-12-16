---
layout: post
title: "A Perceptually Weighted Rank Correlation Indicator for Objective Image Quality Assessment"
date: 2017-05-15 09:24:05
categories: arXiv_CV
tags: arXiv_CV QA Attention Relation
author: Qingbo Wu, Hongliang Li, Fanman Meng, King N. Ngan
mathjax: true
---

* content
{:toc}

##### Abstract
In the field of objective image quality assessment (IQA), the Spearman's $\rho$ and Kendall's $\tau$ are two most popular rank correlation indicators, which straightforwardly assign uniform weight to all quality levels and assume each pair of images are sortable. They are successful for measuring the average accuracy of an IQA metric in ranking multiple processed images. However, two important perceptual properties are ignored by them as well. Firstly, the sorting accuracy (SA) of high quality images are usually more important than the poor quality ones in many real world applications, where only the top-ranked images would be pushed to the users. Secondly, due to the subjective uncertainty in making judgement, two perceptually similar images are usually hardly sortable, whose ranks do not contribute to the evaluation of an IQA metric. To more accurately compare different IQA algorithms, we explore a perceptually weighted rank correlation indicator in this paper, which rewards the capability of correctly ranking high quality images, and suppresses the attention towards insensitive rank mistakes. More specifically, we focus on activating `valid' pairwise comparison towards image quality, whose difference exceeds a given sensory threshold (ST). Meanwhile, each image pair is assigned an unique weight, which is determined by both the quality level and rank deviation. By modifying the perception threshold, we can illustrate the sorting accuracy with a more sophisticated SA-ST curve, rather than a single rank correlation coefficient. The proposed indicator offers a new insight for interpreting visual perception behaviors. Furthermore, the applicability of our indicator is validated in recommending robust IQA metrics for both the degraded and enhanced image data.

##### Abstract (translated by Google)
在客观图像质量评估（IQA）领域，Spearman's $ \ rho $和Kendall $ \ tau $是两个最受欢迎的排名相关指标，它直接为所有质量水平分配统一的权重，并假定每对图像都是可排序的。他们成功地测量了对多个处理过的图像进行排名的IQA指标的平均准确度。但是，它们也忽略了两个重要的感知属性。首先，高质量图像的排序准确性（SA）通常比许多现实世界应用中的劣质质量图像更重要，因为只有排名最高的图像才会被推送给用户。其次，由于主观判断的不确定性，两个感知相似的图像通常很难排序，这些图像对IQA度量的评估没有贡献。为了更准确地比较不同的IQA算法，本文探索了一个感知加权秩相关指标，该指标提高了对高质量图像正确排序的能力，并且抑制了对不敏感级别错误的关注。更具体地说，我们专注于激活“有效”的成对比较，其图像质量的差异超过了一个给定的感官阈值（ST）。同时，每个图像对被分配一个独特的权重，这是由质量等级和等级偏差确定的。通过修改感知阈值，我们可以用更复杂的SA-ST曲线来说明排序的准确性，而不是一个单一的等级相关系数。拟议的指标为解释视觉感知行为提供了新的见解。此外，我们的指标的适用性在推荐降级和增强图像数据的稳健IQA指标方面进行了验证。

##### URL
[https://arxiv.org/abs/1705.05126](https://arxiv.org/abs/1705.05126)

##### PDF
[https://arxiv.org/pdf/1705.05126](https://arxiv.org/pdf/1705.05126)

