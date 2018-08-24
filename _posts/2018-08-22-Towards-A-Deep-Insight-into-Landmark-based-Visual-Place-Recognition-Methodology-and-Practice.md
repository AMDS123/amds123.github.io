---
layout: post
title: "Towards A Deep Insight into Landmark-based Visual Place Recognition: Methodology and Practice"
date: 2018-08-22 21:48:58
categories: arXiv_RO
tags: arXiv_RO Recognition
author: Bo Yang, Jun Li, Xiaosu Xu, Hong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of landmark-based visual place recognition. In the state-of-the-art method, accurate object proposal algorithms are first leveraged for generating a set of local regions containing particular landmarks with high confidence. Then, these candidate regions are represented by deep features and pairwise matching is performed in an exhaustive manner for the similarity measure. Despite its success, conventional object proposal methods usually produce massive landmark-dependent image patches exhibiting significant distribution variance in scale and overlap. As a result, the inconsistency in landmark distributions tends to produce biased similarity between pairwise images yielding the suboptimal performance. In order to gain an insight into the landmark-based place recognition scheme, we conduct a comprehensive study in which the influence of landmark scales and the proportion of overlap on the recognition performance is explored. More specifically, we thoroughly study the exhaustive search based landmark matching mechanism, and thus derive three-fold important observations in terms of the beneficial effect of specific landmark generation strategies. Inspired by the above observations, a simple yet effective dense sampling based scheme is presented for accurate place recognition in this paper. Different from the conventional object proposal strategy, we generate local landmarks of multiple scales with uniform distribution from entire image by dense sampling, and subsequently perform multi-scale fusion on the densely sampled landmarks for similarity measure. The experimental results on three challenging datasets demonstrate that the recognition performance can be significantly improved by our efficient method in which the landmarks are appropriately produced for accurate pairwise matching.

##### Abstract (translated by Google)
在本文中，我们解决了基于地标的视觉位置识别问题。在现有技术方法中，首先利用精确的对象提议算法来生成包含具有高置信度的特定地标的一组局部区域。然后，这些候选区域由深度特征表示，并且对于相似性度量，以穷举的方式执行成对匹配。尽管取得了成功，但传统的对象提议方法通常会产生大量的地标依赖图像块，这些图像块在尺度和重叠方面表现出显着的分布变化结果，界标分布中的不一致倾向于在成对图像之间产生偏差相似性，从而产生次优性能。为了深入了解基于地标的地点识别方案，我们进行了一项综合研究，其中探讨了地标尺度的影响和重叠的比例对识别性能的影响。更具体地说，我们彻底研究基于穷举搜索的地标匹配机制，从而根据特定地标生成策略的有益效果得出三重重要观察结果。受上述观察的启发，本文提出了一种简单而有效的基于密集采样的方案，用于精确的位置识别。与传统的对象提议策略不同，我们通过密集采样从整个图像生成多尺度的均匀分布的局部地标，随后对密集采样的地标进行多尺度融合以进行相似性度量。三个具有挑战性的数据集的实验结果表明，通过我们的有效方法可以显着提高识别性能，其中适当地生成标记以进行精确的成对匹配。

##### URL
[http://arxiv.org/abs/1808.07572](http://arxiv.org/abs/1808.07572)

##### PDF
[http://arxiv.org/pdf/1808.07572](http://arxiv.org/pdf/1808.07572)

