---
layout: post
title: "Constrained-CNN losses forweakly supervised segmentation"
date: 2018-05-12 00:51:54
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention Weakly_Supervised Optimization
author: Hoel Kervadec, Jose Dolz, Meng Tang, Eric Granger, Yuri Boykov, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
Weak supervision, e.g., in the form of partial labels or image tags, is currently attracting significant attention in CNN segmentation as it can mitigate the lack of full and laborious pixel/voxel annotations. Enforcing high-order (global) inequality constraints on the network output, for instance, on the size of the target region, can leverage unlabeled data, guiding training with domain-specific knowledge. Inequality constraints are very flexible because they do not assume exact prior knowledge. However,constrained Lagrangian dual optimization has been largely avoided in deep networks, mainly for computational tractability reasons.To the best of our knowledge, the method of Pathak et al. is the only prior work that addresses deep CNNs with linear constraints in weakly supervised segmentation. It uses the constraints to synthesize fully-labeled training masks (proposals)from weak labels, mimicking full supervision and facilitating dual optimization.We propose to introduce a differentiable term, which enforces inequality constraints directly in the loss function, avoiding expensive Lagrangian dual iterates and proposal generation. From constrained-optimization perspective, our simple approach is not optimal as there is no guarantee that the constraints are satisfied. However, surprisingly,it yields substantially better results than the proposal-based constrained CNNs, while reducing the computational demand for training.In the context of cardiac images, we reached a segmentation performance close to full supervision using a fraction (0.1%) of the full ground-truth labels and image-level tags.While our experiments focused on basic linear constraints such as the target-region size and image tags, our framework can be easily extended to other non-linear constraints.Therefore, it has the potential to close the gap between weakly and fully supervised learning in semantic image segmentation.

##### Abstract (translated by Google)
弱监督，例如以部分标签或图像标签的形式，目前在CNN分割中引起重大关注，因为它可以减轻缺乏完整和费力的像素/体素注释。对网络输出执行高阶（全球）不平等约束，例如，根据目标区域的大小，可以利用未标记的数据，指导具有领域特定知识的培训。不平等约束非常灵活，因为它们不会假定确切的先验知识。然而，在深度网络中基本上避免了约束拉格朗日对偶优化，主要是为了计算易于理解的原因。据我们所知，Pathak等人的方法是在弱监督分割中处理具有线性约束的深CNN的唯一先前工作。它利用约束从弱标签中合成完全标记的训练掩码（提议），模拟全面的监督并促进双重优化。我们建议引入一个可微项，直接在损失函数中实施不等式约束，避免昂贵的拉格朗日对偶迭代和提案一代。从约束优化的角度来看，我们的简单方法并不是最优的，因为不能保证约束满足。然而，令人惊讶的是，它比基于提议的受约束的CNN产生更好的结果，同时减少了对训练的计算需求。在心脏图像的情况下，我们达到了接近完全监督的分割性能，使用分数（0.1％）尽管我们的实验侧重于基本线性约束，如目标区域大小和图像标签，但我们的框架可以很容易地扩展到其他非线性约束。因此，它有可能缩小了语义图像分割中弱监督学习和完全监督学习之间的差距。

##### URL
[https://arxiv.org/abs/1805.04628](https://arxiv.org/abs/1805.04628)

##### PDF
[https://arxiv.org/pdf/1805.04628](https://arxiv.org/pdf/1805.04628)

