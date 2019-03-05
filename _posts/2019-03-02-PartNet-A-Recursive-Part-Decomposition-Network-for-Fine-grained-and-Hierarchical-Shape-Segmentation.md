---
layout: post
title: "PartNet: A Recursive Part Decomposition Network for Fine-grained and Hierarchical Shape Segmentation"
date: 2019-03-02 14:36:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning
author: Fenggen Yu, Kun Liu, Yan Zhang, Chenyang Zhu, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches to 3D shape segmentation are typically formulated as a multi-class labeling problem. Existing models are trained for a fixed set of labels, which greatly limits their flexibility and adaptivity. We opt for top-down recursive decomposition and develop the first deep learning model for hierarchical segmentation of 3D shapes, based on recursive neural networks. Starting from a full shape represented as a point cloud, our model performs recursive binary decomposition, where the decomposition network at all nodes in the hierarchy share weights. At each node, a node classifier is trained to determine the type (adjacency or symmetry) and stopping criteria of its decomposition. The features extracted in higher level nodes are recursively propagated to lower level ones. Thus, the meaningful decompositions in higher levels provide strong contextual cues constraining the segmentations in lower levels. Meanwhile, to increase the segmentation accuracy at each node, we enhance the recursive contextual feature with the shape feature extracted for the corresponding part. Our method segments a 3D shape in point cloud into an unfixed number of parts, depending on the shape complexity, showing strong generality and flexibility. It achieves the state-of-the-art performance, both for fine-grained and semantic segmentation, on the public benchmark and a new benchmark of fine-grained segmentation proposed in this work. We also demonstrate its application for fine-grained part refinements in image-to-shape reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00709](http://arxiv.org/abs/1903.00709)

##### PDF
[http://arxiv.org/pdf/1903.00709](http://arxiv.org/pdf/1903.00709)

