---
layout: post
title: "Constrained-CNN losses for weakly supervised segmentation"
date: 2019-02-08 20:06:55
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention Weakly_Supervised Optimization
author: Hoel Kervadec, Jose Dolz, Meng Tang, Eric Granger, Yuri Boykov, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised learning based on, e.g., partially labelled images or image-tags, is currently attracting significant attention in CNN segmentation as it can mitigate the need for full and laborious pixel/voxel annotations. Enforcing high-order (global) inequality constraints on the network output (for instance, to constrain the size of the target region) can leverage unlabeled data, guiding the training process with domain-specific knowledge. Inequality constraints are very flexible because they do not assume exact prior knowledge. However, constrained Lagrangian dual optimization has been largely avoided in deep networks, mainly for computational tractability reasons. To the best of our knowledge, the method of [Pathak et al., 2015] is the only prior work that addresses deep CNNs with linear constraints in weakly supervised segmentation. It uses the constraints to synthesize fully-labeled training masks (proposals) from weak labels, mimicking full supervision and facilitating dual optimization. We propose to introduce a differentiable penalty, which enforces inequality constraints directly in the loss function, avoiding expensive Lagrangian dual iterates and proposal generation. From constrained-optimization perspective, our simple penalty-based approach is not optimal as there is no guarantee that the constraints are satisfied. However, surprisingly, it yields substantially better results than the Lagrangian-based constrained CNNs in [Pathak et al., 2015], while reducing the computational demand for training. By annotating only a small fraction of the pixels, the proposed approach can reach a level of segmentation performance that is comparable to full supervision on three separate tasks. While our experiments focused on basic linear constraints such as the target-region size and image tags, our framework can be easily extended to other non-linear constraints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.04628](http://arxiv.org/abs/1805.04628)

##### PDF
[http://arxiv.org/pdf/1805.04628](http://arxiv.org/pdf/1805.04628)

