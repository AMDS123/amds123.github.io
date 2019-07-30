---
layout: post
title: "Automated Lesion Detection by Regressing Intensity-Based Distance with a Neural Network"
date: 2019-07-29 14:17:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Kimberlin M.H. van Wijnen, Florian Dubost, Pinar Yilmaz, M. Arfan Ikram, Wiro J. Niessen, Hieab Adams, Meike W. Vernooij, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Localization of focal vascular lesions on brain MRI is an important component of research on the etiology of neurological disorders. However, manual annotation of lesions can be challenging, time-consuming and subject to observer bias. Automated detection methods often need voxel-wise annotations for training. We propose a novel approach for automated lesion detection that can be trained on scans only annotated with a dot per lesion instead of a full segmentation. From the dot annotations and their corresponding intensity images we compute various distance maps (DMs), indicating the distance to a lesion based on spatial distance, intensity distance, or both. We train a fully convolutional neural network (FCN) to predict these DMs for unseen intensity images. The local optima in the predicted DMs are expected to correspond to lesion locations. We show the potential of this approach to detect enlarged perivascular spaces in white matter on a large brain MRI dataset with an independent test set of 1000 scans. Our method matches the intra-rater performance of the expert rater that was computed on an independent set. We compare the different types of distance maps, showing that incorporating intensity information in the distance maps used to train an FCN greatly improves performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12452](http://arxiv.org/abs/1907.12452)

##### PDF
[http://arxiv.org/pdf/1907.12452](http://arxiv.org/pdf/1907.12452)

