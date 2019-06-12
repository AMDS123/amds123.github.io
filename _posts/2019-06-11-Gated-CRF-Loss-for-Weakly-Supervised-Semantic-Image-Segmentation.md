---
layout: post
title: "Gated CRF Loss for Weakly Supervised Semantic Image Segmentation"
date: 2019-06-11 15:23:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation Relation
author: Anton Obukhov, Stamatios Georgoulis, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art approaches for semantic segmentation rely on deep convolutional neural networks trained on fully annotated datasets, that have been shown to be notoriously expensive to collect, both in terms of time and money. To remedy this situation, weakly supervised methods leverage other forms of supervision that require substantially less annotation effort, but they typically present an inability to predict precise object boundaries due to approximate nature of the supervisory signals in those regions. While great progress has been made in improving the performance, many of these weakly supervised methods are highly tailored to their own specific settings. This raises challenges in reusing algorithms and making steady progress. In this paper, we intentionally avoid such practices when tackling weakly supervised semantic segmentation. In particular, we train standard neural networks with partial cross-entropy loss function for the labeled pixels and our proposed Gated CRF loss for the unlabeled pixels. The Gated CRF loss is designed to deliver several important assets: 1) it enables flexibility in the kernel construction to mask out influence from undesired pixel positions; 2) it offloads learning contextual relations to CNN and concentrates on semantic boundaries; 3) it does not rely on high-dimensional filtering and thus has a simple implementation. Throughout the paper we present the advantages of the loss function, analyze several aspects of weakly supervised training, and show that our `purist' approach achieves state-of-the-art performance for both click-based and scribble-based annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04651](http://arxiv.org/abs/1906.04651)

##### PDF
[http://arxiv.org/pdf/1906.04651](http://arxiv.org/pdf/1906.04651)

