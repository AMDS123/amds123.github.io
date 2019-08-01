---
layout: post
title: "Incremental Learning Techniques for Semantic Segmentation"
date: 2019-07-31 09:00:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation Image_Classification Semantic_Segmentation Classification Deep_Learning Detection
author: Umberto Michieli, Pietro Zanuttigh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning architectures exhibit a critical drop of performance due to catastrophic forgetting when they are required to incrementally learn new tasks. Contemporary incremental learning frameworks focus on image classification and object detection while in this work we formally introduce the incremental learning problem for semantic segmentation in which a pixel-wise labeling is considered. To tackle this task we propose to distill the knowledge of the previous model to retain the information about previously learned classes, whilst updating the current model to learn the new ones. We propose various approaches working both on the output logits and on intermediate features. In opposition to some recent frameworks, we do not store any image from previously learned classes and only the last model is needed to preserve high accuracy on these classes. The experimental evaluation on the Pascal VOC2012 dataset shows the effectiveness of the proposed approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13372](http://arxiv.org/abs/1907.13372)

##### PDF
[http://arxiv.org/pdf/1907.13372](http://arxiv.org/pdf/1907.13372)

