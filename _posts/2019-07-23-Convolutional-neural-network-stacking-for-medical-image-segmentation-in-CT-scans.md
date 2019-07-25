---
layout: post
title: "Convolutional neural network stacking for medical image segmentation in CT scans"
date: 2019-07-23 21:11:22
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Marie Kloenne, Sebastian Niehaus, Leonie Lampe, Alberto Merola, Janis Reinelt, Nico Scherf
mathjax: true
---

* content
{:toc}

##### Abstract
Computed tomography (CT) data poses many challenges to medical image segmentation based on convolutional neural networks(CNNs). The main challenges in handling CT scans with CNN are the scale of data (large range of Hounsfield Units) and the processing of the slices. In this paper, we consider a framework, which addresses these demands regarding the data pre-processing, the data augmentation, and the CNN architecture itself. For this purpose, we present a data preprocessing and an augmentation method tailored to CT data. We evaluate and compare different input dimensionalities and two different CNN architectures. One of the architectures is a modified U-Net and the other a modified Mixed-Scale Dense Network (MS-D Net). Thus, we compare dilated convolutions for parallel multi-scale processing to the U-Net approach with traditional scaling operations based on the different input dimensionalities. Finally, we merge a set of 3D modified MS-D Nets and a set of 2D modified U-Nets as a stacked CNN-model to combine the different strengths of both model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10132](http://arxiv.org/abs/1907.10132)

##### PDF
[http://arxiv.org/pdf/1907.10132](http://arxiv.org/pdf/1907.10132)

