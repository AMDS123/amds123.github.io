---
layout: post
title: "Bilateral Cyclic Constraint and Adaptive Regularization for Unsupervised Monocular Depth Prediction"
date: 2019-03-18 08:53:48
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction Relation
author: Alex Wong, Byung-Woo Hong, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning methods to infer (hypothesize) depth of a scene from a single image require costly per-pixel ground-truth. We follow a geometric approach that exploits abundant stereo imagery to learn a model to hypothesize scene structure without direct supervision. Although we train a network with stereo pairs, we only require a single image at test time to hypothesize disparity or depth. We propose a novel objective function that exploits the bilateral cyclic relationship between the left and right disparities and we introduce an adaptive regularization scheme that allows the network to handle both the co-visible and occluded regions in a stereo pair. This process ultimately produces a model to generate hypotheses for the 3-dimensional structure of the scene as viewed in a single image. When used to generate a single (most probable) estimate of depth, our method outperforms state-of-the-art unsupervised monocular depth prediction methods on the KITTI benchmarks. We show that our method generalizes well by applying our models trained on KITTI to the Make3d dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07309](http://arxiv.org/abs/1903.07309)

##### PDF
[http://arxiv.org/pdf/1903.07309](http://arxiv.org/pdf/1903.07309)

