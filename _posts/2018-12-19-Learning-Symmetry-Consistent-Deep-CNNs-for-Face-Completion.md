---
layout: post
title: "Learning Symmetry Consistent Deep CNNs for Face Completion"
date: 2018-12-19 03:25:45
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Xiaoming Li, Ming Liu, Jieru Zhu, Wangmeng Zuo, Meng Wang, Guosheng Hu, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks (CNNs) have achieved great success in face completion to generate plausible facial structures. These methods, however, are limited in maintaining global consistency among face components and recovering fine facial details. On the other hand, reflectional symmetry is a prominent property of face image and benefits face recognition and consistency modeling, yet remaining uninvestigated in deep face completion. In this work, we leverage two kinds of symmetry-enforcing subnets to form a symmetry-consistent CNN model (i.e., SymmFCNet) for effective face completion. For missing pixels on only one of the half-faces, an illumination-reweighted warping subnet is developed to guide the warping and illumination reweighting of the other half-face. As for missing pixels on both of half-faces, we present a generative reconstruction subnet together with a perceptual symmetry loss to enforce symmetry consistency of recovered structures. The SymmFCNet is constructed by stacking generative reconstruction subnet upon illumination-reweighted warping subnet, and can be end-to-end learned from training set of unaligned face images. Experiments show that SymmFCNet can generate high quality results on images with synthetic and real occlusion, and performs favorably against state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07741](http://arxiv.org/abs/1812.07741)

##### PDF
[http://arxiv.org/pdf/1812.07741](http://arxiv.org/pdf/1812.07741)

