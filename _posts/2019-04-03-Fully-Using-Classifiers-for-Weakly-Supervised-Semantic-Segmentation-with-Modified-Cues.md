---
layout: post
title: "Fully Using Classifiers for Weakly Supervised Semantic Segmentation with Modified Cues"
date: 2019-04-03 03:30:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Semantic_Segmentation
author: Ting Sun, Lei Tai, Zhihan Gao, Ming Liu, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel weakly-supervised semantic segmentation method using image-level label only. The class-specific activation maps from the well-trained classifiers are used as cues to train a segmentation network. The well-known defects of these cues are coarseness and incompleteness. We use super-pixel to refine them, and fuse the cues extracted from both a color image trained classifier and a gray image trained classifier to compensate for their incompleteness. The conditional random field is adapted to regulate the training process and to refine the outputs further. Besides initializing the segmentation network, the previously trained classifier is also used in the testing phase to suppress the non-existing classes. Experimental results on the PASCAL VOC 2012 dataset illustrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01749](https://arxiv.org/abs/1904.01749)

##### PDF
[https://arxiv.org/pdf/1904.01749](https://arxiv.org/pdf/1904.01749)

