---
layout: post
title: "Incremental Learning for Semantic Segmentation of Large-Scale Remote Sensing Data"
date: 2018-10-29 22:51:52
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Onur Tasar, Yuliya Tarabalka, Pierre Alliez
mathjax: true
---

* content
{:toc}

##### Abstract
In spite of remarkable success of the convolutional neural networks on semantic segmentation, they suffer from catastrophic forgetting: a significant performance drop for the already learned classes when new classes are added on the data, having no annotations for the old classes. We propose an incremental learning methodology, enabling to learn segmenting new classes without hindering dense labeling abilities for the previous classes, although the entire previous data are not accessible. The key points of the proposed approach are adapting the network to learn new as well as old classes on the new training data, and allowing it to remember the previously learned information for the old classes. For adaptation, we keep a frozen copy of the previously trained network, which is used as a memory for the updated network in absence of annotations for the former classes. The updated network minimizes a loss function, which balances the discrepancy between outputs for the previous classes from the memory and updated networks, and the mis-classification rate between outputs for the new classes from the updated network and the new ground-truth. For remembering, we either regularly feed samples from the stored, little fraction of the previous data or use the memory network, depending on whether the new data are collected from completely different geographic areas or from the same city. Our experimental results prove that it is possible to add new classes to the network, while maintaining its performance for the previous classes, despite the whole previous training data are not available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12448](http://arxiv.org/abs/1810.12448)

##### PDF
[http://arxiv.org/pdf/1810.12448](http://arxiv.org/pdf/1810.12448)

