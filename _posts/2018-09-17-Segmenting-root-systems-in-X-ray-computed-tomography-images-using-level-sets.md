---
layout: post
title: "Segmenting root systems in X-ray computed tomography images using level sets"
date: 2018-09-17 18:31:51
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Amy Tabb, Keith E. Duncan, Christopher N. Topp
mathjax: true
---

* content
{:toc}

##### Abstract
The segmentation of plant roots from soil and other growing media in X-ray computed tomography images is needed to effectively study the root system architecture without excavation. However, segmentation is a challenging problem in this context because the root and non-root regions share similar features. In this paper, we describe a method based on level sets and specifically adapted for this segmentation problem. In particular, we deal with the issues of using a level sets approach on large image volumes for root segmentation, and track active regions of the front using an occupancy grid. This method allows for straightforward modifications to a narrow-band algorithm such that excessive forward and backward movements of the front can be avoided, distance map computations in a narrow band context can be done in linear time through modification of Meijster et al.'s distance transform algorithm, and regions of the image volume are iteratively used to estimate distributions for root versus non-root classes. Results are shown of three plant species of different maturity levels, grown in three different media. Our method compares favorably to a state-of-the-art method for root segmentation in X-ray CT image volumes.

##### Abstract (translated by Google)
需要在X射线计算机断层扫描图像中对土壤和其他生长介质中的植物根部进行分割，以便在不进行挖掘的情况下有效地研究根系结构。但是，在此上下文中，分段是一个具有挑战性的问题，因为根和非根区域共享相似的功能。在本文中，我们描述了一种基于水平集的方法，并且特别适用于该分割问题。特别是，我们处理在大图像体积上使用水平集方法进行根分割的问题，并使用占用网格跟踪前方的活动区域。该方法允许对窄带算法进行直接修改，从而可以避免前方的过度前向和后向移动，通过修改Meijster等人的距离，可以在线性时间内完成窄带上下文中的距离图计算。转换算法和图像体积的区域被迭代地用于估计根与非根类的分布。显示了在三种不同培养基中生长的三种不同成熟度水平的植物物种的结果。我们的方法有利地与用于X射线CT图像体积中的根分割的现有技术方法相比。

##### URL
[https://arxiv.org/abs/1809.06398](https://arxiv.org/abs/1809.06398)

##### PDF
[https://arxiv.org/pdf/1809.06398](https://arxiv.org/pdf/1809.06398)

