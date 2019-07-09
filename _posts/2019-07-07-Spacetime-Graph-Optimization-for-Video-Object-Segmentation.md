---
layout: post
title: "Spacetime Graph Optimization for Video Object Segmentation"
date: 2019-07-07 18:05:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Emanuela Haller, Adina Magda Florea, Marius Leordeanu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the challenging task of object discovery and segmentation in video. We introduce an efficient method that can be applied in supervised and unsupervised scenarios, using a graph-based representation in both space and time. Our method exploits the consistency in appearance and motion patterns of pixels belonging to the same object. We formulate the task as a clustering problem: graph nodes at the pixel level that belong to the object of interest should form a strong cluster, linked through long range optical flow chains and with similar motion and appearance features along those chains. On one hand, the optimization problem aims to maximize the segmentation clustering score based on the structure of pixel motions through space and time. On the other, the segmentation should be consistent with the features at the level of nodes, s.t. these features should be able to predict the segmentation labels. The solution to our problem relates to spectral clustering as well as to the classical regression analysis. It leads to a fast algorithm that converges in a few iterations to a global optimum of the relaxed problem, using fixed point iteration. The proposed method, namely GO-VOS, is relatively fast and accurate. It can be used both as a standalone and completely unsupervised method or in combination with other segmentation methods. In experiments, we demonstrate top performance on several challenging datasets: DAVIS, SegTrack and YouTube-Objects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03326](http://arxiv.org/abs/1907.03326)

##### PDF
[http://arxiv.org/pdf/1907.03326](http://arxiv.org/pdf/1907.03326)

