---
layout: post
title: "Composition-Aware Image Aesthetics Assessment"
date: 2019-07-25 02:22:16
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Dong Liu, Rohit Puri, Nagendra Kamath, Subhabrata Bhattachary
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic image aesthetics assessment is important for a wide variety of applications such as on-line photo suggestion, photo album management and image retrieval. Previous methods have focused on mapping the holistic image content to a high or low aesthetics rating. However, the composition information of an image characterizes the harmony of its visual elements according to the principles of art, and provides richer information for learning aesthetics. In this work, we propose to model the image composition information as the mutual dependency of its local regions, and design a novel architecture to leverage such information to boost the performance of aesthetics assessment. To achieve this, we densely partition an image into local regions and compute aesthetics-preserving features over the regions to characterize the aesthetics properties of image content. With the feature representation of local regions, we build a region composition graph in which each node denotes one region and any two nodes are connected by an edge weighted by the similarity of the region features. We perform reasoning on this graph via graph convolution, in which the activation of each node is determined by its highly correlated neighbors. Our method naturally uncovers the mutual dependency of local regions in the network training procedure, and achieves the state-of-the-art performance on the benchmark visual aesthetics datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10801](http://arxiv.org/abs/1907.10801)

##### PDF
[http://arxiv.org/pdf/1907.10801](http://arxiv.org/pdf/1907.10801)

