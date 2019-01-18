---
layout: post
title: "Domain Adaptation for Structured Output via Discriminative Patch Representations"
date: 2019-01-17 03:06:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Semantic_Segmentation
author: Yi-Hsuan Tsai, Kihyuk Sohn, Samuel Schulter, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting structured outputs such as semantic segmentation relies on expensive per-pixel annotations to learn strong supervised models like convolutional neural networks. However, these models trained on one data domain may not generalize well to other domains unequipped with annotations for model finetuning. To avoid the labor-intensive process of annotation, we develop a domain adaptation method to adapt the source data to the unlabeled target domain. To this end, we propose to learn discriminative feature representations of patches based on label histograms in the source domain, through the construction of a clustered space. With such representations as guidance, we then use an adversarial learning scheme to push the feature representations in target patches to the closer distributions in source ones. In addition, we show that our framework can integrate a global alignment process with the proposed patch-level alignment and achieve state-of-the-art performance on semantic segmentation. Extensive ablation studies and experiments are conducted on numerous benchmark datasets with various settings, such as synthetic-to-real and cross-city scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05427](http://arxiv.org/abs/1901.05427)

##### PDF
[http://arxiv.org/pdf/1901.05427](http://arxiv.org/pdf/1901.05427)

