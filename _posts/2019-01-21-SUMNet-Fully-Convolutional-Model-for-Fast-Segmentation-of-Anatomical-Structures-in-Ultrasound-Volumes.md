---
layout: post
title: "SUMNet: Fully Convolutional Model for Fast Segmentation of Anatomical Structures in Ultrasound Volumes"
date: 2019-01-21 13:16:18
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Semantic_Segmentation Relation
author: Sumanth Nandamuri, Debarghya China, Pabitra Mitra, Debdoot Sheet
mathjax: true
---

* content
{:toc}

##### Abstract
Ultrasound imaging is generally employed for real-time investigation of internal anatomy of the human body for disease identification. Delineation of the anatomical boundary of organs and pathological lesions is quite challenging due to the stochastic nature of speckle intensity in the images, which also introduces visual fatigue for the observer. This paper introduces a fully convolutional neural network based method to segment organ and pathologies in ultrasound volume by learning the spatial-relationship between closely related classes in the presence of stochastically varying speckle intensity. We propose a convolutional encoder-decoder like framework with (i) feature concatenation across matched layers in encoder and decoder and (ii) index passing based unpooling at the decoder for semantic segmentation of ultrasound volumes. We have experimentally evaluated the performance on publicly available datasets consisting of $10$ intravascular ultrasound pullback acquired at $20$ MHz and $16$ freehand thyroid ultrasound volumes acquired $11 - 16$ MHz. We have obtained a dice score of $0.93 \pm 0.08$ and $0.92 \pm 0.06$ respectively, following a $10$-fold cross-validation experiment while processing frame of $256 \times 384$ pixel in $0.035$s and a volume of $256 \times 384 \times 384$ voxel in $13.44$s.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06920](http://arxiv.org/abs/1901.06920)

##### PDF
[http://arxiv.org/pdf/1901.06920](http://arxiv.org/pdf/1901.06920)

