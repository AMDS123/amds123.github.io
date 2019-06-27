---
layout: post
title: "Instance Segmentation by Jointly Optimizing Spatial Embeddings and Clustering Bandwidth"
date: 2019-06-26 13:58:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Davy Neven, Bert De Brabandere, Marc Proesmans, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art instance segmentation methods are not suited for real-time applications like autonomous driving, which require fast execution times at high accuracy. Although the currently dominant proposal-based methods have high accuracy, they are slow and generate masks at a fixed and low resolution. Proposal-free methods, by contrast, can generate masks at high resolution and are often faster, but fail to reach the same accuracy as the proposal-based methods. In this work we propose a new clustering loss function for proposal-free instance segmentation. The loss function pulls the spatial embeddings of pixels belonging to the same instance together and jointly learns an instance-specific clustering bandwidth, maximizing the intersection-over-union of the resulting instance mask. When combined with a fast architecture, the network can perform instance segmentation in real-time while maintaining a high accuracy. We evaluate our method on the challenging Cityscapes benchmark and achieve top results (5\% improvement over Mask R-CNN) at more than 10 fps on 2MP images. Code is available at https://github.com/davyneven/SpatialEmbeddings

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11109](http://arxiv.org/abs/1906.11109)

##### PDF
[http://arxiv.org/pdf/1906.11109](http://arxiv.org/pdf/1906.11109)

