---
layout: post
title: "Saliency guided deep network for weakly-supervised image segmentation"
date: 2018-10-19 07:35:40
categories: arXiv_CV
tags: arXiv_CV Salient Sparse Segmentation Attention Classification
author: Fengdong Sun, Wenhui Li
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised image segmentation is an important task in computer vision. A key problem is how to obtain high quality objects location from image-level category. Classification activation mapping is a common method which can be used to generate high-precise object location cues. However these location cues are generally very sparse and small such that they can not provide effective information for image segmentation. In this paper, we propose a saliency guided image segmentation network to resolve this problem. We employ a self-attention saliency method to generate subtle saliency maps, and render the location cues grow as seeds by seeded region growing method to expand pixel-level labels extent. In the process of seeds growing, we use the saliency values to weight the similarity between pixels to control the growing. Therefore saliency information could help generate discriminative object regions, and the effects of wrong salient pixels can be suppressed efficiently. Experimental results on a common segmentation dataset PASCAL VOC2012 demonstrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08378](http://arxiv.org/abs/1810.08378)

##### PDF
[http://arxiv.org/pdf/1810.08378](http://arxiv.org/pdf/1810.08378)

