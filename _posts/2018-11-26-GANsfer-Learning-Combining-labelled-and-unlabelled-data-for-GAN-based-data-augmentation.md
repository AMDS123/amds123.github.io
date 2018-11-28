---
layout: post
title: "GANsfer Learning: Combining labelled and unlabelled data for GAN based data augmentation"
date: 2018-11-26 20:08:44
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Christopher Bowles, Roger Gunn, Alexander Hammers, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Medical imaging is a domain which suffers from a paucity of manually annotated data for the training of learning algorithms. Manually delineating pathological regions at a pixel level is a time consuming process, especially in 3D images, and often requires the time of a trained expert. As a result, supervised machine learning solutions must make do with small amounts of labelled data, despite there often being additional unlabelled data available. Whilst of less value than labelled images, these unlabelled images can contain potentially useful information. In this paper we propose combining both labelled and unlabelled data within a GAN framework, before using the resulting network to produce images for use when training a segmentation network. We explore the task of deep grey matter multi-class segmentation in an AD dataset and show that the proposed method leads to a significant improvement in segmentation results, particularly in cases where the amount of labelled data is restricted. We show that this improvement is largely driven by a greater ability to segment the structures known to be the most affected by AD, thereby demonstrating the benefits of exposing the system to more examples of pathological anatomical variation. We also show how a shift in domain of the training data from young and healthy towards older and more pathological examples leads to better segmentations of the latter cases, and that this leads to a significant improvement in the ability for the computed segmentations to stratify cases of AD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10669](http://arxiv.org/abs/1811.10669)

##### PDF
[http://arxiv.org/pdf/1811.10669](http://arxiv.org/pdf/1811.10669)

