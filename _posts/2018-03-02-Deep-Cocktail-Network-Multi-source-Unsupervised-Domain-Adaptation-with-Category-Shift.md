---
layout: post
title: "Deep Cocktail Network: Multi-source Unsupervised Domain Adaptation with Category Shift"
date: 2018-03-02 12:58:51
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Ruijia Xu, Ziliang Chen, Wangmeng Zuo, Junjie Yan, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaptation (UDA) conventionally assumes labeled source samples coming from a single underlying source distribution. Whereas in practical scenario, labeled data are typically collected from diverse sources. The multiple sources are different not only from the target but also from each other, thus, domain adaptater should not be modeled in the same way. Moreover, those sources may not completely share their categories, which further brings a new transfer challenge called category shift. In this paper, we propose a deep cocktail network (DCTN) to battle the domain and category shifts among multiple sources. Motivated by the theoretical results in \cite{mansour2009domain}, the target distribution can be represented as the weighted combination of source distributions, and, the multi-source unsupervised domain adaptation via DCTN is then performed as two alternating steps: i) It deploys multi-way adversarial learning to minimize the discrepancy between the target and each of the multiple source domains, which also obtains the source-specific perplexity scores to denote the possibilities that a target sample belongs to different source domains. ii) The multi-source category classifiers are integrated with the perplexity scores to classify target sample, and the pseudo-labeled target samples together with source samples are utilized to update the multi-source category classifier and the feature extractor. We evaluate DCTN in three domain adaptation benchmarks, which clearly demonstrate the superiority of our framework.

##### Abstract (translated by Google)
无监督域适应（UDA）通常假定来自单个底层源分布的标记源样本。而在实际情况中，标记数据通常是从不同来源收集的。多个来源不仅与目标有所不同，而且相互之间也不相同，因此，不应该以相同的方式对领域适应者进行建模。此外，这些来源可能不完全分享他们的类别，这进一步带来了一个新的转移挑战，称为类别转变。在本文中，我们提出了一个深度鸡尾酒网络（DCTN）来对抗来自多个来源的领域和类别转变。目标分布可以表示为源分布的加权组合，并且通过DCTN的多源无监督域自适应然后作为两个交替步骤执行：i）它部署多个进行对抗学习以最小化目标与多个源域中的每一个之间的差异，其还获得源特定的困惑评分以表示目标样本属于不同源域的可能性。 ii）将多源分类器与困惑分数相结合以对目标样本进行分类，并将伪标签目标样本与源样本一起用于更新多源分类器和特征提取器。我们评估了三个域适应基准的DCTN，这清楚地表明了我们框架的优越性。

##### URL
[http://arxiv.org/abs/1803.00830](http://arxiv.org/abs/1803.00830)

##### PDF
[http://arxiv.org/pdf/1803.00830](http://arxiv.org/pdf/1803.00830)

