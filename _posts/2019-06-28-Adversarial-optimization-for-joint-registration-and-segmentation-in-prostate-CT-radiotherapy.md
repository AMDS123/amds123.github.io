---
layout: post
title: "Adversarial optimization for joint registration and segmentation in prostate CT radiotherapy"
date: 2019-06-28 13:55:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Optimization Deep_Learning Quantitative
author: Mohamed S. Elmahdy, Jelmer M. Wolterink, Hessam Sokooti, Ivana I&#x161;gum, Marius Staring
mathjax: true
---

* content
{:toc}

##### Abstract
Joint image registration and segmentation has long been an active area of research in medical imaging. Here, we reformulate this problem in a deep learning setting using adversarial learning. We consider the case in which fixed and moving images as well as their segmentations are available for training, while segmentations are not available during testing; a common scenario in radiotherapy. The proposed framework consists of a 3D end-to-end generator network that estimates the deformation vector field (DVF) between fixed and moving images in an unsupervised fashion and applies this DVF to the moving image and its segmentation. A discriminator network is trained to evaluate how well the moving image and segmentation align with the fixed image and segmentation. The proposed network was trained and evaluated on follow-up prostate CT scans for image-guided radiotherapy, where the planning CT contours are propagated to the daily CT images using the estimated DVF. A quantitative comparison with conventional registration using \texttt{elastix} showed that the proposed method improved performance and substantially reduced computation time, thus enabling real-time contour propagation necessary for online-adaptive radiotherapy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12223](http://arxiv.org/abs/1906.12223)

##### PDF
[http://arxiv.org/pdf/1906.12223](http://arxiv.org/pdf/1906.12223)

