---
layout: post
title: "Decoupled Deep Neural Network for Semi-supervised Semantic Segmentation"
date: 2015-06-17 08:38:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Seunghoon Hong, Hyeonwoo Noh, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep neural network architecture for semi-supervised semantic segmentation using heterogeneous annotations. Contrary to existing approaches posing semantic segmentation as a single task of region-based classification, our algorithm decouples classification and segmentation, and learns a separate network for each task. In this architecture, labels associated with an image are identified by classification network, and binary segmentation is subsequently performed for each identified label in segmentation network. The decoupled architecture enables us to learn classification and segmentation networks separately based on the training data with image-level and pixel-wise class labels, respectively. It facilitates to reduce search space for segmentation effectively by exploiting class-specific activation maps obtained from bridging layers. Our algorithm shows outstanding performance compared to other semi-supervised approaches even with much less training images with strong annotations in PASCAL VOC dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1506.04924](https://arxiv.org/abs/1506.04924)

##### PDF
[https://arxiv.org/pdf/1506.04924](https://arxiv.org/pdf/1506.04924)

