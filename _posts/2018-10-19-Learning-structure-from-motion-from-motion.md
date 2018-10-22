---
layout: post
title: "Learning structure-from-motion from motion"
date: 2018-10-19 16:09:37
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Cl&#xe9;ment Pinard, Laure Chevalley, Antoine Manzanera, David Filliat
mathjax: true
---

* content
{:toc}

##### Abstract
This work is based on a questioning of the quality metrics used by deep neural networks performing depth prediction from a single image, and then of the usability of recently published works on unsupervised learning of depth from videos. To overcome their limitations, we propose to learn in the same unsupervised manner a depth map inference system from monocular videos that takes a pair of images as input. This algorithm actually learns structure-from-motion from motion, and not only structure from context appearance. The scale factor issue is explicitly treated, and the absolute depth map can be estimated from camera displacement magnitude, which can be easily measured from cheap external sensors. Our solution is also much more robust with respect to domain variation and adaptation via fine tuning, because it does not rely entirely in depth from context. Two use cases are considered, unstabilized moving camera videos, and stabilized ones. This choice is motivated by the UAV (for Unmanned Aerial Vehicle) use case that generally provides reliable orientation measurement. We provide a set of experiments showing that, used in real conditions where only speed can be known, our network outperforms competitors for most depth quality measures. Results are given on the well known KITTI dataset, which provides robust stabilization for our second use case, but also contains moving scenes which are very typical of the in-car road context. We then present results on a synthetic dataset that we believe to be more representative of typical UAV scenes. Lastly, we present two domain adaptation use cases showing superior robustness of our method compared to single view depth algorithms, which indicates that it is better suited for highly variable visual contexts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.04471](http://arxiv.org/abs/1809.04471)

##### PDF
[http://arxiv.org/pdf/1809.04471](http://arxiv.org/pdf/1809.04471)

