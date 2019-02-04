---
layout: post
title: "Projection-Based 2.5D U-net Architecture for Fast Volumetric Segmentation"
date: 2019-02-01 14:19:00
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN
author: Christoph Angermann, Markus Haltmeier, Ruth Steiger, Sergiy Pereverzyev Jr, Elke Gizewski
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks are state-of-the-art for various segmentation tasks. While for 2D images these networks are also computationally efficient, 3D convolutions have huge storage requirements and require long training time. To overcome this issue, we introduce a network structure for volumetric data without 3D convolution layers. The main idea is to integrate projection layers to transform the volumetric data to a sequence of images, where each image contains information of the full data. We then apply 2D convolutions to the projection images followed by lifting to a volumetric data. The proposed network structure can be trained in much less time than any 3D-network and still shows accurate performance for a sparse binary segmentation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00347](http://arxiv.org/abs/1902.00347)

##### PDF
[http://arxiv.org/pdf/1902.00347](http://arxiv.org/pdf/1902.00347)

