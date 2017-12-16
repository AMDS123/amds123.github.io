---
layout: post
title: "Mind the Class Weight Bias: Weighted Maximum Mean Discrepancy for Unsupervised Domain Adaptation"
date: 2017-05-01 17:54:53
categories: arXiv_CV
tags: arXiv_CV Classification
author: Hongliang Yan, Yukang Ding, Peihua Li, Qilong Wang, Yong Xu, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
In domain adaptation, maximum mean discrepancy (MMD) has been widely adopted as a discrepancy metric between the distributions of source and target domains. However, existing MMD-based domain adaptation methods generally ignore the changes of class prior distributions, i.e., class weight bias across domains. This remains an open problem but ubiquitous for domain adaptation, which can be caused by changes in sample selection criteria and application scenarios. We show that MMD cannot account for class weight bias and results in degraded domain adaptation performance. To address this issue, a weighted MMD model is proposed in this paper. Specifically, we introduce class-specific auxiliary weights into the original MMD for exploiting the class prior probability on source and target domains, whose challenge lies in the fact that the class label in target domain is unavailable. To account for it, our proposed weighted MMD model is defined by introducing an auxiliary weight for each class in the source domain, and a classification EM algorithm is suggested by alternating between assigning the pseudo-labels, estimating auxiliary weights and updating model parameters. Extensive experiments demonstrate the superiority of our weighted MMD over conventional MMD for domain adaptation.

##### Abstract (translated by Google)
在领域适应中，最大平均差异（MMD）已被广泛采用作为源域和目标域分布之间的差异度量。然而，现有的基于MMD的域适配方法通常忽略了类先验分布的变化，即跨域的类别权重偏差。这仍然是一个开放的问题，但是无处不在的领域适应，这可能是由样本选择标准和应用场景的变化造成的。我们表明，MMD不能解释类的权重偏差，并导致降级的域适应性能。为了解决这个问题，本文提出了一个加权MMD模型。具体而言，我们在原始MMD中引入了类别特定的辅助权重，以利用源和目标域上的类别先验概率，其挑战在于目标域中的类别标签不可用。为了说明这一点，我们提出的加权MMD模型是通过引入源域中每个类别的辅助权重来定义的，并且通过交替分配伪标签，估计辅助权重和更新模型参数来建议分类EM算法。大量的实验证明了我们的加权MMD优于传统MMD的领域适应的优越性。

##### URL
[https://arxiv.org/abs/1705.00609](https://arxiv.org/abs/1705.00609)

##### PDF
[https://arxiv.org/pdf/1705.00609](https://arxiv.org/pdf/1705.00609)

