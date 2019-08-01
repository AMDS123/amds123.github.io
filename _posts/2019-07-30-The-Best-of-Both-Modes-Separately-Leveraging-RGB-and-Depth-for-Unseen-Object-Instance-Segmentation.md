---
layout: post
title: "The Best of Both Modes: Separately Leveraging RGB and Depth for Unseen Object Instance Segmentation"
date: 2019-07-30 21:35:33
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Christopher Xie, Yu Xiang, Arsalan Mousavian, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
In order to function in unstructured environments, robots need the ability to recognize unseen novel objects. We take a step in this direction by tackling the problem of segmenting unseen object instances in tabletop environments. However, the type of large-scale real-world dataset required for this task typically does not exist for most robotic settings, which motivates the use of synthetic data. We propose a novel method that separately leverages synthetic RGB and synthetic depth for unseen object instance segmentation. Our method is comprised of two stages where the first stage operates only on depth to produce rough initial masks, and the second stage refines these masks with RGB. Surprisingly, our framework is able to learn from synthetic RGB-D data where the RGB is non-photorealistic. To train our method, we introduce a large-scale synthetic dataset of random objects on tabletops. We show that our method, trained on this dataset, can produce sharp and accurate masks, outperforming state-of-the-art methods on unseen object instance segmentation. We also show that our method can segment unseen objects for robot grasping. Code, models and video can be found at https://rse-lab.cs.washington.edu/projects/unseen-object-instance-segmentation/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13236](http://arxiv.org/abs/1907.13236)

##### PDF
[http://arxiv.org/pdf/1907.13236](http://arxiv.org/pdf/1907.13236)

