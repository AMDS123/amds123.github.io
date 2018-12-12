---
layout: post
title: "Zero-Shot Learning with Sparse Attribute Propagation"
date: 2018-12-11 14:28:20
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Nanyi Fei, Jiajun Liu, Jiechao Guan, Zhiwu Lu, Tao Xiang, Ji-Rong Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) aims to recognize a set of unseen classes without any training images. The standard approach to ZSL requires a semantic descriptor for each class/instance, with attribute vector being the most widely used. Attribute annotation is expensive; it thus severely limits the scalability of ZSL. In this paper, we define a new ZSL setting where only a few images are annotated with attributes from each seen class. This is clearly more challenging yet more realistic than the conventional ZSL setting. To overcome the attribute sparsity under our new ZSL setting, we propose a novel inductive ZSL model termed sparse attribute propagation (SAP) by propagating attribute annotations to more unannotated images using sparse coding. This is followed by learning bidirectional projections between features and attributes for ZSL. An efficient solver is provided, together with rigorous theoretic algorithm analysis. With our SAP, we show that a ZSL training dataset can now be augmented by the abundant web images returned by image search engine, to further improve the model performance. Moreover, the general applicability of SAP is demonstrated on solving the social image annotation (SIA) problem. Extensive experiments show that our model achieves superior performance on both ZSL and SIA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04427](http://arxiv.org/abs/1812.04427)

##### PDF
[http://arxiv.org/pdf/1812.04427](http://arxiv.org/pdf/1812.04427)

