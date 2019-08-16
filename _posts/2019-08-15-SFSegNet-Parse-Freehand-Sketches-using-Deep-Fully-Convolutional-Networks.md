---
layout: post
title: "SFSegNet: Parse Freehand Sketches using Deep Fully Convolutional Networks"
date: 2019-08-15 01:35:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Deep_Learning
author: Junkun Jiang, Ruomei Wang, Shujin Lin, Fei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Parsing sketches via semantic segmentation is attractive but challenging, because (i) free-hand drawings are abstract with large variances in depicting objects due to different drawing styles and skills; (ii) distorting lines drawn on the touchpad make sketches more difficult to be recognized; (iii) the high-performance image segmentation via deep learning technologies needs enormous annotated sketch datasets during the training stage. In this paper, we propose a Sketch-target deep FCN Segmentation Network(SFSegNet) for automatic free-hand sketch segmentation, labeling each sketch in a single object with multiple parts. SFSegNet has an end-to-end network process between the input sketches and the segmentation results, composed of 2 parts: (i) a modified deep Fully Convolutional Network(FCN) using a reweighting strategy to ignore background pixels and classify which part each pixel belongs to; (ii) affine transform encoders that attempt to canonicalize the shaking strokes. We train our network with the dataset that consists of 10,000 annotated sketches, to find an extensively applicable model to segment stokes semantically in one ground truth. Extensive experiments are carried out and segmentation results show that our method outperforms other state-of-the-art networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05389](http://arxiv.org/abs/1908.05389)

##### PDF
[http://arxiv.org/pdf/1908.05389](http://arxiv.org/pdf/1908.05389)

