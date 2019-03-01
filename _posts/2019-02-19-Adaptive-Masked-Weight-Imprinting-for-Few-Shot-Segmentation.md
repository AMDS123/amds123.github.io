---
layout: post
title: "Adaptive Masked Weight Imprinting for Few-Shot Segmentation"
date: 2019-02-19 22:28:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding Semantic_Segmentation Deep_Learning Relation
author: Mennatullah Siam, Boris Oreshkin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has mainly thrived by training on large-scale datasets. However, for a continual learning agent it is critical to incrementally update its model in a sample efficient manner. Learning semantic segmentation from few labelled samples can be a significant step toward such goal. We propose a novel method that constructs the new class weights from few labelled samples in the support set without back-propagation, while updating the previously learned classes. Inspiring from the work on adaptive correlation filters, an adaptive masked imprinted weights method is designed. It utilizes a masked average pooling layer on the output embeddings and acts as a positive proxy for that class. Our proposed method is evaluated on PASCAL-5i dataset and outperforms the state of the art in the 5-shot semantic segmentation. Unlike previous methods, our proposed approach does not require a second branch to estimate parameters or prototypes, and enables the adaptation of previously learned weights. Our adaptation scheme is evaluated on DAVIS video segmentation benchmark and our proposed incremental version of PASCAL and has shown to outperform the baseline model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11123](http://arxiv.org/abs/1902.11123)

##### PDF
[http://arxiv.org/pdf/1902.11123](http://arxiv.org/pdf/1902.11123)

