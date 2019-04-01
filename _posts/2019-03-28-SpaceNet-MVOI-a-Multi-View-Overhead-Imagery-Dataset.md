---
layout: post
title: "SpaceNet MVOI: a Multi-View Overhead Imagery Dataset"
date: 2019-03-28 19:51:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Nicholas Weir, David Lindenbaum, Alexei Bastidas, Adam Van Etten, Sean McPherson, Jacob Shermeyer, Varun Kumar, Hanlin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Detection and segmentation of objects in overheard imagery is a challenging task. The variable density, random orientation, small size, and instance-to-instance heterogeneity of objects in overhead imagery calls for approaches distinct from existing models designed for natural scene datasets. Though new overhead imagery datasets are being developed, they almost universally comprise a single view taken from directly overhead ("at nadir"), failing to address one critical variable: look angle. By contrast, views vary in real-world overhead imagery, particularly in dynamic scenarios such as natural disasters where first looks are often over 40 degrees off-nadir. This represents an important challenge to computer vision methods, as changing view angle adds distortions, alters resolution, and changes lighting. At present, the impact of these perturbations for algorithmic detection and segmentation of objects is untested. To address this problem, we introduce the SpaceNet Multi-View Overhead Imagery (MVOI) Dataset, an extension of the SpaceNet open source remote sensing dataset. MVOI comprises 27 unique looks from a broad range of viewing angles (-32 to 54 degrees). Each of these images cover the same geography and are annotated with 126,747 building footprint labels, enabling direct assessment of the impact of viewpoint perturbation on model performance. We benchmark multiple leading segmentation and object detection models on: (1) building detection, (2) generalization to unseen viewing angles and resolutions, and (3) sensitivity of building footprint extraction to changes in resolution. We find that segmentation and object detection models struggle to identify buildings in off-nadir imagery and generalize poorly to unseen views, presenting an important benchmark to explore the broadly relevant challenge of detecting small, heterogeneous target objects in visually dynamic contexts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12239](http://arxiv.org/abs/1903.12239)

##### PDF
[http://arxiv.org/pdf/1903.12239](http://arxiv.org/pdf/1903.12239)

