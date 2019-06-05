---
layout: post
title: "Localization in Aerial Imagery with Grid Maps using LocGAN"
date: 2019-06-04 15:53:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Haohao Hu, Junyi Zhu, Sascha Wirges, Martin Lauer
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present LocGAN, our localization approach based on a geo-referenced aerial imagery and LiDAR grid maps. Currently, most self-localization approaches relate the current sensor observations to a map generated from previously acquired data. Unfortunately, this data is not always available and the generated maps are usually sensor setup specific. Global Navigation Satellite Systems (GNSS) can overcome this problem. However, they are not always reliable especially in urban areas due to multi-path and shadowing effects. Since aerial imagery is usually available, we can use it as prior information. To match aerial images with grid maps, we use conditional Generative Adversarial Networks (cGANs) which transform aerial images to the grid map domain. The transformation between the predicted and measured grid map is estimated using a localization network (LocNet). Given the geo-referenced aerial image transformation the vehicle pose can be estimated. Evaluations performed on the data recorded in region Karlsruhe, Germany show that our LocGAN approach provides reliable global localization results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01540](http://arxiv.org/abs/1906.01540)

##### PDF
[http://arxiv.org/pdf/1906.01540](http://arxiv.org/pdf/1906.01540)

