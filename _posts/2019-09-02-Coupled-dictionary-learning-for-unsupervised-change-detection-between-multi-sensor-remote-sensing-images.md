---
layout: post
title: "Coupled dictionary learning for unsupervised change detection between multi-sensor remote sensing images"
date: 2019-09-02 13:44:07
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Vinicius Ferraris, Nicolas Dobigeon, Yanna Cavalcanti, Thomas Oberlin, Marie Chabert
mathjax: true
---

* content
{:toc}

##### Abstract
Archetypal scenarios for change detection generally consider two images acquired through sensors of the same modality. However, in some specific cases such as emergency situations, the only images available may be those acquired through sensors of different modalities. This paper addresses the problem of unsupervisedly detecting changes between two observed images acquired by sensors of different modalities with possibly different resolutions. These sensor dissimilarities introduce additional issues in the context of operational change detection that are not addressed by most of the classical methods. This paper introduces a novel framework to effectively exploit the available information by modelling the two observed images as a sparse linear combination of atoms belonging to a pair of coupled overcomplete dictionaries learnt from each observed image. As they cover the same geographical location, codes are expected to be globally similar, except for possible changes in sparse spatial locations. Thus, the change detection task is envisioned through a dual code estimation which enforces spatial sparsity in the difference between the estimated codes associated with each image. This problem is formulated as an inverse problem which is iteratively solved using an efficient proximal alternating minimization algorithm accounting for nonsmooth and nonconvex functions. The proposed method is applied to real images with simulated yet realistic and real changes. A comparison with state-of-the-art change detection methods evidences the accuracy of the proposed strategy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08118](http://arxiv.org/abs/1807.08118)

##### PDF
[http://arxiv.org/pdf/1807.08118](http://arxiv.org/pdf/1807.08118)

