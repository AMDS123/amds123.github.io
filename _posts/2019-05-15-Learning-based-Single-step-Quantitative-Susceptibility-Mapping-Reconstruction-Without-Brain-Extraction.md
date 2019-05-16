---
layout: post
title: "Learning-based Single-step Quantitative Susceptibility Mapping Reconstruction Without Brain Extraction"
date: 2019-05-15 05:55:58
categories: arXiv_AI
tags: arXiv_AI Face Quantitative Relation
author: Hongjiang Wei, Steven Cao, Yuyao Zhang, Xiaojun Guan, Fuhua Yan, Kristen W. Yeom, Chunlei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative susceptibility mapping (QSM) estimates the underlying tissue magnetic susceptibility from MRI gradient-echo phase signal and typically requires several processing steps. These steps involve phase unwrapping, brain volume extraction, background phase removal and solving an ill-posed inverse problem. The resulting susceptibility map is known to suffer from inaccuracy near the edges of the brain tissues, in part due to imperfect brain extraction, edge erosion of the brain tissue and the lack of phase measurement outside the brain. This inaccuracy has thus hindered the application of QSM for measuring the susceptibility of tissues near the brain edges, e.g., quantifying cortical layers and generating superficial venography. To address these challenges, we propose a learning-based QSM reconstruction method that directly estimates the magnetic susceptibility from total phase images without the need for brain extraction and background phase removal, referred to as autoQSM. The neural network has a modified U-net structure and is trained using QSM maps computed by a two-step QSM method. 209 healthy subjects with ages ranging from 11 to 82 years were employed for patch-wise network training. The network was validated on data dissimilar to the training data, e.g. in vivo mouse brain data and brains with lesions, which suggests that the network has generalized and learned the underlying mathematical relationship between magnetic field perturbation and magnetic susceptibility. AutoQSM was able to recover magnetic susceptibility of anatomical structures near the edges of the brain including the veins covering the cortical surface, spinal cord and nerve tracts near the mouse brain boundaries. The advantages of high-quality maps, no need for brain volume extraction and high reconstruction speed demonstrate its potential for future applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05953](http://arxiv.org/abs/1905.05953)

##### PDF
[http://arxiv.org/pdf/1905.05953](http://arxiv.org/pdf/1905.05953)

