---
layout: post
title: "Mitigating the Hubness Problem for Zero-Shot Learning of 3D Objects"
date: 2019-07-15 08:47:14
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Ali Cheraghian, Shafin Rahman, Dylan Campbell, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
The development of advanced 3D sensors has enabled many objects to be captured in the wild at a large scale, and a 3D object recognition system may therefore encounter many objects for which the system has received no training. Zero-Shot Learning (ZSL) approaches can assist such systems in recognizing previously unseen objects. Applying ZSL to 3D point cloud objects is an emerging topic in the area of 3D vision, however, a significant problem that ZSL often suffers from is the so-called hubness problem, which is when a model is biased to predict only a few particular labels for most of the test instances. We observe that this hubness problem is even more severe for 3D recognition than for 2D recognition. One reason for this is that in 2D one can use pre-trained networks trained on large datasets like ImageNet, which produces high-quality features. However, in the 3D case there are no such large-scale, labelled datasets available for pre-training which means that the extracted 3D features are of poorer quality which, in turn, exacerbates the hubness problem. In this paper, we therefore propose a loss to specifically address the hubness problem. Our proposed method is effective for both Zero-Shot and Generalized Zero-Shot Learning, and we perform extensive evaluations on the challenging datasets ModelNet40, ModelNet10, McGill and SHREC2015. A new state-of-the-art result for both zero-shot tasks in the 3D case is established.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06371](http://arxiv.org/abs/1907.06371)

##### PDF
[http://arxiv.org/pdf/1907.06371](http://arxiv.org/pdf/1907.06371)

