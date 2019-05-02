---
layout: post
title: "Cycle-Consistent Speech Enhancement"
date: 2019-04-30 15:48:14
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Zhong Meng, Jinyu Li, Yifan Gong, Biing-Hwang (Fred) Juang
mathjax: true
---

* content
{:toc}

##### Abstract
Feature mapping using deep neural networks is an effective approach for single-channel speech enhancement. Noisy features are transformed to the enhanced ones through a mapping network and the mean square errors between the enhanced and clean features are minimized. In this paper, we propose a cycle-consistent speech enhancement (CSE) in which an additional inverse mapping network is introduced to reconstruct the noisy features from the enhanced ones. A cycle-consistent constraint is enforced to minimize the reconstruction loss. Similarly, a backward cycle of mappings is performed in the opposite direction with the same networks and losses. With cycle-consistency, the speech structure is well preserved in the enhanced features while noise is effectively reduced such that the feature-mapping network generalizes better to unseen data. In cases where only unparalleled noisy and clean data is available for training, two discriminator networks are used to distinguish the enhanced and noised features from the clean and noisy ones. The discrimination losses are jointly optimized with reconstruction losses through adversarial multi-task learning. Evaluated on the CHiME-3 dataset, the proposed CSE achieves 19.60% and 6.69% relative word error rate improvements respectively when using or without using parallel clean and noisy speech data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.02253](http://arxiv.org/abs/1809.02253)

##### PDF
[http://arxiv.org/pdf/1809.02253](http://arxiv.org/pdf/1809.02253)

