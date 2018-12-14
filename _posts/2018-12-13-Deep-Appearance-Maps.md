---
layout: post
title: "Deep Appearance Maps"
date: 2018-12-13 13:15:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Optimization Deep_Learning Gradient_Descent Relation
author: Maxim Maximov, Tobias Ritschel, Laura Leal-Taix&#xe9;, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep representation of appearance, i.e. the relation of color, surface orientation, viewer position, material and illumination. Previous approaches have used deep learning to extract classic appearance representations relating to reflectance model parameters (e.g. Phong) or illumination (e.g. HDR environment maps). We suggest to directly represent appearance itself as a network we call a deep appearance map (DAM). This is a 4D generalization over 2D reflectance maps, which held the view direction fixed. First, we show how a DAM can be learned from images or video frames and later be used to synthesize appearance, given new surface orientations and viewer positions. Second, we demonstrate how another network can be used to map from an image or video frames to a DAM network to reproduce this appearance, without using a lengthy optimization such as stochastic gradient descent (learning-to-learn). Finally, we show the example of an appearance estimation-and-segmentation task, mapping from an image showing multiple materials to multiple deep appearance maps.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00863](http://arxiv.org/abs/1804.00863)

##### PDF
[http://arxiv.org/pdf/1804.00863](http://arxiv.org/pdf/1804.00863)

