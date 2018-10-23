---
layout: post
title: "SG-One: Similarity Guidance Network for One-Shot Semantic Segmentation"
date: 2018-10-22 05:30:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Relation
author: Xiaolin Zhang, Yunchao Wei, Yi Yang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
One-shot semantic segmentation poses a challenging task of recognizing the object regions from unseen categories with only one annotated example as supervision. In this paper, we propose a simple yet effective Similarity Guidance network to tackle the One-shot (SG-One) segmentation problem. We aim at predicting the segmentation mask of a query image with the reference to one densely labeled support image. To obtain the robust representative feature of the support image, we firstly propose a masked average pooling strategy for producing the guidance features using only the pixels belonging to the support image. We then leverage the cosine similarity to build the relationship between the guidance features and features of pixels from the query image. In this way, the possibilities embedded in the produced similarity maps can be adopted to guide the process of segmenting objects. Furthermore, our SG-One is a unified framework which can efficiently process both support and query images within one network and be learned in an end-to-end manner. We conduct extensive experiments on Pascal VOC 2012. In particular, our SG-One achieves the mIoU score of 46.3%, which outperforms the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09091](http://arxiv.org/abs/1810.09091)

##### PDF
[http://arxiv.org/pdf/1810.09091](http://arxiv.org/pdf/1810.09091)

