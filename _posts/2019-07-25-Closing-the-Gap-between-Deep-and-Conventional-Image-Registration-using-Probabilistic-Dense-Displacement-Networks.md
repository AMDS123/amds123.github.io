---
layout: post
title: "Closing the Gap between Deep and Conventional Image Registration using Probabilistic Dense Displacement Networks"
date: 2019-07-25 09:44:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Deep_Learning
author: Mattias P. Heinrich
mathjax: true
---

* content
{:toc}

##### Abstract
Nonlinear image registration continues to be a fundamentally important tool in medical image analysis. Diagnostic tasks, image-guided surgery and radiotherapy as well as motion analysis all rely heavily on accurate intra-patient alignment. Furthermore, inter-patient registration enables atlas-based segmentation or landmark localisation and shape analysis. When labelled scans are scarce and anatomical differences large, conventional registration has often remained superior to deep learning methods that have so far mainly dealt with relatively small or low-complexity deformations. We address this shortcoming by leveraging ideas from probabilistic dense displacement optimisation that has excelled in many registration tasks with large deformations. We propose to design a network with approximate min-convolutions and mean field inference for differentiable displacement regularisation within a discrete weakly-supervised registration setting. By employing these meaningful and theoretically proven constraints, our learnable registration algorithm contains very few trainable weights (primarily for feature extraction) and is easier to train with few labelled scans. It is very fast in training and inference and achieves state-of-the-art accuracies for the challenging inter-patient registration of abdominal CT outperforming previous deep learning approaches by 15% Dice overlap.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10931](http://arxiv.org/abs/1907.10931)

##### PDF
[http://arxiv.org/pdf/1907.10931](http://arxiv.org/pdf/1907.10931)

