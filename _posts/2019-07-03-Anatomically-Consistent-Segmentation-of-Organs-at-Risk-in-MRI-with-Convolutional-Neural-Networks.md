---
layout: post
title: "Anatomically Consistent Segmentation of Organs at Risk in MRI with Convolutional Neural Networks"
date: 2019-07-03 15:55:43
categories: arXiv_AI
tags: arXiv_AI Segmentation GAN CNN Deep_Learning Quantitative
author: Pawel Mlynarski, Herv&#xe9; Delingette, Hamza Alghamdi, Pierre-Yves Bondiau, Nicholas Ayache
mathjax: true
---

* content
{:toc}

##### Abstract
Planning of radiotherapy involves accurate segmentation of a large number of organs at risk, i.e. organs for which irradiation doses should be minimized to avoid important side effects of the therapy. We propose a deep learning method for segmentation of organs at risk inside the brain region, from Magnetic Resonance (MR) images. Our system performs segmentation of eight structures: eye, lens, optic nerve, optic chiasm, pituitary gland, hippocampus, brainstem and brain. We propose an efficient algorithm to train neural networks for an end-to-end segmentation of multiple and non-exclusive classes, addressing problems related to computational costs and missing ground truth segmentations for a subset of classes. We enforce anatomical consistency of the result in a postprocessing step, in particular we introduce a graph-based algorithm for segmentation of the optic nerves, enforcing the connectivity between the eyes and the optic chiasm. We report cross-validated quantitative results on a database of 44 contrast-enhanced T1-weighted MRIs with provided segmentations of the considered organs at risk, which were originally used for radiotherapy planning. In addition, the segmentations produced by our model on an independent test set of 50 MRIs are evaluated by an experienced radiotherapist in order to qualitatively assess their accuracy. The mean distances between produced segmentations and the ground truth ranged from 0.1 mm to 0.7 mm across different organs. A vast majority (96 %) of the produced segmentations were found acceptable for radiotherapy planning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02003](http://arxiv.org/abs/1907.02003)

##### PDF
[http://arxiv.org/pdf/1907.02003](http://arxiv.org/pdf/1907.02003)

