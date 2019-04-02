---
layout: post
title: "MortonNet: Self-Supervised Learning of Local Features in 3D Point Clouds"
date: 2019-03-30 15:12:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation RNN
author: Ali Thabet, Humam Alwassel, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
We present a self-supervised task on point clouds, in order to learn meaningful point-wise features that encode local structure around each point. Our self-supervised network, named MortonNet, operates directly on unstructured/unordered point clouds. Using a multi-layer RNN, MortonNet predicts the next point in a point sequence created by a popular and fast Space Filling Curve, the Morton-order curve. The final RNN state (coined Morton feature) is versatile and can be used in generic 3D tasks on point clouds. In fact, we show how Morton features can be used to significantly improve performance (+3% for 2 popular semantic segmentation algorithms) in the task of semantic segmentation of point clouds on the challenging and large-scale S3DIS dataset. We also show how MortonNet trained on S3DIS transfers well to another large-scale dataset, vKITTI, leading to an improvement over state-of-the-art of 3.8%. Finally, we use Morton features to train a much simpler and more stable model for part segmentation in ShapeNet. Our results show how our self-supervised task results in features that are useful for 3D segmentation tasks, and generalize well to other datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00230](http://arxiv.org/abs/1904.00230)

##### PDF
[http://arxiv.org/pdf/1904.00230](http://arxiv.org/pdf/1904.00230)

