---
layout: post
title: "Stacked Spatio-Temporal Graph Convolutional Networks for Action Segmentation"
date: 2019-04-14 18:15:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Action_Recognition CNN Inference Recognition
author: Pallabi Ghosh, Yi Yao, Larry S. Davis, Ajay Divakaran
mathjax: true
---

* content
{:toc}

##### Abstract
We propose novel Stacked Spatio-Temporal Graph Convolutional Networks (Stacked-STGCN) for action segmentation, i.e., predicting and localizing a sequence of actions over long videos. We extend the Spatio-Temporal Graph Convolutional Network (STGCN) originally proposed for skeleton-based action recognition to enable nodes with different characteristics (e.g., scene, actor, object, action, etc.), feature descriptors with varied lengths, and arbitrary temporal edge connections to account for large graph deformation commonly associated with complex activities. We further introduce the stacked hourglass architecture to STGCN to leverage the advantages of an encoder-decoder design for improved generalization performance and localization accuracy. We explore various descriptors such as frame-level VGG, segment-level I3D, RCNN-based object, etc. as node descriptors to enable action segmentation based on joint inference over comprehensive contextual information. We show results on CAD120 (which provides pre-computed node features and edge weights for fair performance comparison across algorithms) as well as a more complex real-world activity dataset, Charades. Our Stacked-STGCN in general achieves 4.0% performance improvement over the best reported results in F1 score on CAD120 and 1.3% in mAP on Charades using VGG features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10575](http://arxiv.org/abs/1811.10575)

##### PDF
[http://arxiv.org/pdf/1811.10575](http://arxiv.org/pdf/1811.10575)

