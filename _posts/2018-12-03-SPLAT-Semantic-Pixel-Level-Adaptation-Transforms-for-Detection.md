---
layout: post
title: "SPLAT: Semantic Pixel-Level Adaptation Transforms for Detection"
date: 2018-12-03 17:38:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN Semantic_Segmentation Detection
author: Eric Tzeng, Kaylee Burns, Kate Saenko, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation of visual detectors is a critical challenge, yet existing methods have overlooked pixel appearance transformations, focusing instead on bootstrapping and/or domain confusion losses. We propose a Semantic Pixel-Level Adaptation Transform (SPLAT) approach to detector adaptation that efficiently generates cross-domain image pairs. Our model uses aligned-pair and/or pseudo-label losses to adapt an object detector to the target domain, and can learn transformations with or without densely labeled data in the source (e.g. semantic segmentation annotations). Without dense labels, as is the case when only detection labels are available in the source, transformations are learned using CycleGAN alignment. Otherwise, when dense labels are available we introduce a more efficient cycle-free method, which exploits pixel-level semantic labels to condition the training of the transformation network. The end task is then trained using detection box labels from the source, potentially including labels inferred on unlabeled source data. We show both that pixel-level transforms outperform prior approaches to detector domain adaptation, and that our cycle-free method outperforms prior models for unconstrained cycle-based learning of generic transformations while running 3.8 times faster. Our combined model improves on prior detection baselines by 12.5 mAP adapting from Sim 10K to Cityscapes, recovering over 50% of the missing performance between the unadapted baseline and the labeled-target upper bound.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00929](http://arxiv.org/abs/1812.00929)

##### PDF
[http://arxiv.org/pdf/1812.00929](http://arxiv.org/pdf/1812.00929)

