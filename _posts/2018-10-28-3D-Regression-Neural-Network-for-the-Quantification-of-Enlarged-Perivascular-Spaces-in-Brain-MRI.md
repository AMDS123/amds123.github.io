---
layout: post
title: "3D Regression Neural Network for the Quantification of Enlarged Perivascular Spaces in Brain MRI"
date: 2018-10-28 22:52:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN CNN Detection Relation
author: Florian Dubost, Hieab Adams, Gerda Bortsova, M. Arfan Ikram, Wiro Niessen, Meike Vernooij, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Enlarged perivascular spaces (EPVS) in the brain are an emerging imaging marker for cerebral small vessel disease, and have been shown to be related to increased risk of various neurological diseases, including stroke and dementia. Automatic quantification of EPVS would greatly help to advance research into its etiology and its potential as a risk indicator of disease. We propose a convolutional network regression method to quantify the extent of EPVS in the basal ganglia from 3D brain MRI. We first segment the basal ganglia and subsequently apply a 3D convolutional regression network designed for small object detection within this region of interest. The network takes an image as input, and outputs a quantification score of EPVS. The network has significantly more convolution operations than pooling ones and no final activation, allowing it to span the space of real numbers. We validated our approach using a dataset of 2000 brain MRI scans scored visually. Experiments with varying sizes of training and test sets showed that a good performance can be achieved with a training set of only 200 scans. With a training set of 1000 scans, the intraclass correlation coefficient (ICC) between our scoring method and the expert's visual score was 0.74. Our method outperforms by a large margin - more than 0.10 - four more conventional automated approaches based on intensities, scale-invariant feature transform, and random forest. We show that the network learns the structures of interest and investigate the influence of hyper-parameters on the performance. We also evaluate the reproducibility of our network using a set of 60 subjects scanned twice (scan-rescan reproducibility). On this set our network achieves an ICC of 0.93, while the intrarater agreement reaches 0.80. Furthermore, the automatic EPVS scoring correlates similarly to age as visual scoring.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.05914](http://arxiv.org/abs/1802.05914)

##### PDF
[http://arxiv.org/pdf/1802.05914](http://arxiv.org/pdf/1802.05914)

