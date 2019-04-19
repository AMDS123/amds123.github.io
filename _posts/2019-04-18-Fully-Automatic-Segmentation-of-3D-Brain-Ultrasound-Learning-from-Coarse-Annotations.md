---
layout: post
title: "Fully Automatic Segmentation of 3D Brain Ultrasound: Learning from Coarse Annotations"
date: 2019-04-18 09:51:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Julia Rackerseder, R&#xfc;diger G&#xf6;bl, Nassir Navab, Christoph Hennersperger
mathjax: true
---

* content
{:toc}

##### Abstract
Intra-operative ultrasound is an increasingly important imaging modality in neurosurgery. However, manual interaction with imaging data during the procedures, for example to select landmarks or perform segmentation, is difficult and can be time consuming. Yet, as registration to other imaging modalities is required in most cases, some annotation is necessary. We propose a segmentation method based on DeepVNet and specifically evaluate the integration of pre-training with simulated ultrasound sweeps to improve automatic segmentation and enable a fully automatic initialization of registration. In this view, we show that despite training on coarse and incomplete semi-automatic annotations, our approach is able to capture the desired superficial structures such as \textit{sulci}, the \textit{cerebellar tentorium}, and the \textit{falx cerebri}. We perform a five-fold cross-validation on the publicly available RESECT dataset. Trained on the dataset alone, we report a Dice and Jaccard coefficient of $0.45 \pm 0.09$ and $0.30 \pm 0.07$ respectively, as well as an average distance of $0.78 \pm 0.36~mm$. With the suggested pre-training, we computed a Dice and Jaccard coefficient of $0.47 \pm 0.10$ and $0.31 \pm 0.08$, and an average distance of $0.71 \pm 0.38~mm$. The qualitative evaluation suggest that with pre-training the network can learn to generalize better and provide refined and more complete segmentations in comparison to incomplete annotations provided as input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08655](http://arxiv.org/abs/1904.08655)

##### PDF
[http://arxiv.org/pdf/1904.08655](http://arxiv.org/pdf/1904.08655)

