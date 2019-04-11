---
layout: post
title: "3D Object Instance Recognition and Pose Estimation Using Triplet Loss with Dynamic Margin"
date: 2019-04-09 18:09:12
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation CNN Recognition
author: Sergey Zakharov, Wadim Kehl, Benjamin Planche, Andreas Hutter, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of 3D object instance recognition and pose estimation of localized objects in cluttered environments using convolutional neural networks. Inspired by the descriptor learning approach of Wohlhart et al., we propose a method that introduces the dynamic margin in the manifold learning triplet loss function. Such a loss function is designed to map images of different objects under different poses to a lower-dimensional, similarity-preserving descriptor space on which efficient nearest neighbor search algorithms can be applied. Introducing the dynamic margin allows for faster training times and better accuracy of the resulting low-dimensional manifolds. Furthermore, we contribute the following: adding in-plane rotations (ignored by the baseline method) to the training, proposing new background noise types that help to better mimic realistic scenarios and improve accuracy with respect to clutter, adding surface normals as another powerful image modality representing an object surface leading to better performance than merely depth, and finally implementing an efficient online batch generation that allows for better variability during the training phase. We perform an exhaustive evaluation to demonstrate the effects of our contributions. Additionally, we assess the performance of the algorithm on the large BigBIRD dataset to demonstrate good scalability properties of the pipeline with respect to the number of models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04854](http://arxiv.org/abs/1904.04854)

##### PDF
[http://arxiv.org/pdf/1904.04854](http://arxiv.org/pdf/1904.04854)

