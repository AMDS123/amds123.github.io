---
layout: post
title: "Multi-branch Convolutional Neural Network for Multiple Sclerosis Lesion Segmentation"
date: 2018-11-07 15:42:57
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Shahab Aslani, Michael Dayan, Loredana Storelli, Massimo Filippi, Vittorio Murino, Maria A Rocca, Diego Sona
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an automated approach for segmenting multiple sclerosis (MS) lesions from multi-modal brain magnetic resonance images. Our method is based on a deep end-to-end 2D convolutional neural network (CNN) for slice-based segmentation of 3D volumetric data. The proposed CNN includes a multi-branch down-sampling path, which enables the network to encode slices from multiple modalities separately. Multi-scale feature fusion blocks are proposed to combine feature-maps from different modalities at different stages of the network. Then, multi-scale feature up-sampling blocks are proposed to upsize combined feature-maps with different resolutions to leverage information from the lesion's shape and location. We trained and tested our model using orthogonal plane orientations of each 3D modality to exploit the contextual information in all directions. The proposed pipeline is evaluated on two different datasets, a private dataset including 37 MS patients and a publicly available dataset known as the ISBI 2015 longitudinal MS lesion segmentation challenge dataset, consisting of 14 MS patients. Considering the ISBI challenge, at the time of submission, our method was amongst the top performing solutions. On the private dataset, using the same array of performance metrics as in the ISBI challenge, the proposed approach shows high improvements in MS lesion segmentation comparing with other publicly available tools.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02942](http://arxiv.org/abs/1811.02942)

##### PDF
[http://arxiv.org/pdf/1811.02942](http://arxiv.org/pdf/1811.02942)

