---
layout: post
title: "Single Network Panoptic Segmentation for Street Scene Understanding"
date: 2019-02-07 15:18:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction
author: Daan de Geus, Panagiotis Meletis, Gijs Dubbelman
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a single deep neural network for panoptic segmentation, for which the goal is to provide each individual pixel of an input image with a class label, as in semantic segmentation, as well as a unique identifier for specific objects in an image, following instance segmentation. Our network makes joint semantic and instance segmentation predictions and combines these to form an output in the panoptic format. This has two main benefits: firstly, the entire panoptic prediction is made in one pass, reducing the required computation time and resources; secondly, by learning the tasks jointly, information is shared between the two tasks, thereby improving performance. Our network is evaluated on two street scene datasets: Cityscapes and Mapillary Vistas. By leveraging information exchange and improving the merging heuristics, we increase the performance of the single network, and achieve a score of 23.9 on the Panoptic Quality (PQ) metric on Mapillary Vistas validation, with an input resolution of 640 x 900 pixels. On Cityscapes validation, our method achieves a PQ score of 45.9 with an input resolution of 512 x 1024 pixels. Moreover, our method decreases the prediction time by a factor of 2 with respect to separate networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02678](http://arxiv.org/abs/1902.02678)

##### PDF
[http://arxiv.org/pdf/1902.02678](http://arxiv.org/pdf/1902.02678)

