---
layout: post
title: "Detect What You Can: Detecting and Representing Objects using Holistic Models and Body Parts"
date: 2014-06-08 21:44:18
categories: arXiv_CV
tags: arXiv_CV
author: Xianjie Chen, Roozbeh Mottaghi, Xiaobai Liu, Sanja Fidler, Raquel Urtasun, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting objects becomes difficult when we need to deal with large shape deformation, occlusion and low resolution. We propose a novel approach to i) handle large deformations and partial occlusions in animals (as examples of highly deformable objects), ii) describe them in terms of body parts, and iii) detect them when their body parts are hard to detect (e.g., animals depicted at low resolution). We represent the holistic object and body parts separately and use a fully connected model to arrange templates for the holistic object and body parts. Our model automatically decouples the holistic object or body parts from the model when they are hard to detect. This enables us to represent a large number of holistic object and body part combinations to better deal with different "detectability" patterns caused by deformations, occlusion and/or low resolution. We apply our method to the six animal categories in the PASCAL VOC dataset and show that our method significantly improves state-of-the-art (by 4.1% AP) and provides a richer representation for objects. During training we use annotations for body parts (e.g., head, torso, etc), making use of a new dataset of fully annotated object parts for PASCAL VOC 2010, which provides a mask for each part.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1406.2031](https://arxiv.org/abs/1406.2031)

##### PDF
[https://arxiv.org/pdf/1406.2031](https://arxiv.org/pdf/1406.2031)

