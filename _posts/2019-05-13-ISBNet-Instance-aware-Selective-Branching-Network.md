---
layout: post
title: "ISBNet: Instance-aware Selective Branching Network"
date: 2019-05-13 03:45:42
categories: arXiv_AI
tags: arXiv_AI NAS Inference
author: Shaofeng Cai, Yao Shu, Wei Wang, Beng Chin Ooi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed growing interests in designing efficient neural networks and neural architecture search (NAS). Although remarkable efficiency and accuracy have been achieved, existing expert designed and NAS models neglect that input instances are of varying complexity thus different amount of computation is required. Therefore, inference with a fixed model that processes all instances through the same transformations would waste plenty of computational resources. Customizing the model capacity in an instance-aware manner is highly demanded. In this paper, we introduce a novel network ISBNet to address this issue, which supports efficient instance-level inference by selectively bypassing transformation branches of infinitesimal importance weight. We also propose lightweight hypernetworks SelectionNet to generate these importance weights instance-wisely. Extensive experiments have been conducted to evaluate the efficiency of ISBNet and the results show that ISBNet achieves extremely efficient inference comparing to existing networks. For example, ISBNet takes only 12.45% parameters and 45.79% FLOPs of the state-of-the-art efficient network ShuffleNetV2 with comparable accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04849](http://arxiv.org/abs/1905.04849)

##### PDF
[http://arxiv.org/pdf/1905.04849](http://arxiv.org/pdf/1905.04849)

