---
layout: post
title: "Domain Adaptive Segmentation in Volume Electron Microscopy Imaging"
date: 2018-10-23 09:12:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Joris Roels, Julian Hennies, Yvan Saeys, Wilfried Philips, Anna Kreshuk
mathjax: true
---

* content
{:toc}

##### Abstract
In the last years, automated segmentation has become a necessary tool for volume electron microscopy (EM) imaging. So far, the best performing techniques have been largely based on fully supervised encoder-decoder CNNs, requiring a substantial amount of annotated images. Domain Adaptation (DA) aims to alleviate the annotation burden by 'adapting' the networks trained on existing groundtruth data (source domain) to work on a different (target) domain with as little additional annotation as possible. Most DA research is focused on the classification task, whereas volume EM segmentation remains rather unexplored. In this work, we extend recently proposed classification DA techniques to an encoder-decoder layout and propose a novel method that adds a reconstruction decoder to the classical encoder-decoder segmentation in order to align source and target encoder features. The method has been validated on the task of segmenting mitochondria in EM volumes. We have performed DA from brain EM images to HeLa cells and from isotropic FIB/SEM volumes to anisotropic TEM volumes. In all cases, the proposed method has outperformed the extended classification DA techniques and the finetuning baseline. An implementation of our work can be found on https://github.com/JorisRoels/domain-adaptive-segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09734](http://arxiv.org/abs/1810.09734)

##### PDF
[http://arxiv.org/pdf/1810.09734](http://arxiv.org/pdf/1810.09734)

