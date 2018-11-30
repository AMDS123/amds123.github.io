---
layout: post
title: "Semantic Part Detection via Matching: Learning to Generalize to Novel Viewpoints from Limited Training Data"
date: 2018-11-28 20:48:18
categories: arXiv_CV
tags: arXiv_CV Detection
author: Yutong Bai, Qing Liu, Lingxi Xie, Yan Zheng, Weichao Qiu, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting semantic parts of an object is a challenging task in computer vision, particularly because it is hard to construct large annotated datasets due to the difficulty of annotating semantic parts. In this paper we present an approach which learns from a small training dataset of annotated semantic parts, where the object is seen from a limited range of viewpoints, but generalizes to detect semantic parts from a much larger range of viewpoints. Our approach is based on a matching algorithm for finding accurate spatial correspondence between two images, which enables semantic parts annotated on one image to be transplanted to another. In particular, this enables images in the training dataset to be matched to a virtual 3D model of the object (for simplicity, we assume that the object viewpoint can be estimated by standard techniques). Then a clustering algorithm is used to annotate the semantic parts of the 3D virtual model. This virtual 3D model can be used to synthesize annotated images from a large range of viewpoint. These can be matched to images in the test set, using the same matching algorithm, to detect semantic parts in novel viewpoints of the object. Our algorithm is very simple, intuitive, and contains very few parameters. We evaluate our approach in the car subclass of the VehicleSemanticPart dataset. We show it outperforms standard deep network approaches and, in particular, performs much better on novel viewpoints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11823](http://arxiv.org/abs/1811.11823)

##### PDF
[http://arxiv.org/pdf/1811.11823](http://arxiv.org/pdf/1811.11823)

