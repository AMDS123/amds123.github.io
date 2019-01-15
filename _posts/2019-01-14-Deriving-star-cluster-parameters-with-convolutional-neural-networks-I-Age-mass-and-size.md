---
layout: post
title: "Deriving star cluster parameters with convolutional neural networks. I. Age, mass, and size"
date: 2019-01-14 08:06:49
categories: arXiv_CV
tags: arXiv_CV Survey CNN Inference Classification Detection
author: J. Bialopetravi&#x10d;ius, D. Narbutis, V. Vansevi&#x10d;ius
mathjax: true
---

* content
{:toc}

##### Abstract
Context. Convolutional neural networks (CNNs) have been proven to perform fast classification and detection on natural images and have potential to infer astrophysical parameters on the exponentially increasing amount of sky survey imaging data. The inference pipeline can be trained either from real human-annotated data or simulated mock observations. Until now star cluster analysis was based on integral or individual resolved stellar photometry. This limits the amount of information that can be extracted from cluster images. 
 Aims. Develop a CNN-based algorithm aimed to simultaneously derive ages, masses, and sizes of star clusters directly from multi-band images. Demonstrate CNN capabilities on low mass semi-resolved star clusters in a low signal-to-noise ratio regime. 
 Methods. A CNN was constructed based on the deep residual network (ResNet) architecture and trained on simulated images of star clusters with various ages, masses, and sizes. To provide realistic backgrounds, M31 star fields taken from the PHAT survey were added to the mock cluster images. 
 Results. The proposed CNN was verified on mock images of artificial clusters and has demonstrated high precision and no significant bias for clusters of ages $\lesssim$3Gyr and masses between 250 and 4,000 ${\rm M_\odot}$. The pipeline is end-to-end, starting from input images all the way to the inferred parameters; no hand-coded steps have to be performed: estimates of parameters are provided by the neural network in one inferential step from raw images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.07658](http://arxiv.org/abs/1807.07658)

##### PDF
[http://arxiv.org/pdf/1807.07658](http://arxiv.org/pdf/1807.07658)

