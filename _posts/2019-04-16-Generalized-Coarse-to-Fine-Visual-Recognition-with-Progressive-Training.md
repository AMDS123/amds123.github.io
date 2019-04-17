---
layout: post
title: "Generalized Coarse-to-Fine Visual Recognition with Progressive Training"
date: 2019-04-16 03:43:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Classification Prediction Recognition
author: Xutong Ren, Lingxi Xie, Chen Wei, Siyuan Qiao, Chi Su, Jiaying Liu, Qi Tian, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision is difficult, partly because the desired mathematical function connecting input and output data is often complex, fuzzy and thus hard to learn. Coarse-to-fine (C2F) learning is a promising direction, but it remains unclear how it is applied to a wide range of vision problems. 
 This paper presents a generalized C2F framework by making two technical contributions. First, we provide a unified way of C2F propagation, in which the coarse prediction (a class vector, a detected box, a segmentation mask, etc.) is encoded into a dense (pixel-level) matrix and concatenated to the original input, so that the fine model takes the same design of the coarse model but sees additional information. Second, we present a progressive training strategy which starts with feeding the ground-truth instead of the coarse output into the fine model, and gradually increases the fraction of coarse output, so that at the end of training the fine model is ready for testing. We also relate our approach to curriculum learning by showing that data difficulty keeps increasing during the training process. We apply our framework to three vision tasks including image classification, object localization and semantic segmentation, and demonstrate consistent accuracy gain compared to the baseline training strategy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12047](http://arxiv.org/abs/1811.12047)

##### PDF
[http://arxiv.org/pdf/1811.12047](http://arxiv.org/pdf/1811.12047)

