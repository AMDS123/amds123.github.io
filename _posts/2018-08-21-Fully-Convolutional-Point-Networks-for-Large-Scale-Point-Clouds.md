---
layout: post
title: "Fully-Convolutional Point Networks for Large-Scale Point Clouds"
date: 2018-08-21 10:58:57
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Caption CNN Prediction Relation
author: Dario Rethage, Johanna Wald, Jürgen Sturm, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a general-purpose, fully-convolutional network architecture for efficiently processing large-scale 3D data. One striking characteristic of our approach is its ability to process unorganized 3D representations such as point clouds as input, then transforming them internally to ordered structures to be processed via 3D convolutions. In contrast to conventional approaches that maintain either unorganized or organized representations, from input to output, our approach has the advantage of operating on memory efficient input data representations while at the same time exploiting the natural structure of convolutional operations to avoid the redundant computing and storing of spatial information in the network. The network eliminates the need to pre- or post process the raw sensor data. This, together with the fully-convolutional nature of the network, makes it an end-to-end method able to process point clouds of huge spaces or even entire rooms with up to 200k points at once. Another advantage is that our network can produce either an ordered output or map predictions directly onto the input cloud, thus making it suitable as a general-purpose point cloud descriptor applicable to many 3D tasks. We demonstrate our network's ability to effectively learn both low-level features as well as complex compositional relationships by evaluating it on benchmark datasets for semantic voxel segmentation, semantic part segmentation and 3D scene captioning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.06840](https://arxiv.org/abs/1808.06840)

##### PDF
[https://arxiv.org/pdf/1808.06840](https://arxiv.org/pdf/1808.06840)

