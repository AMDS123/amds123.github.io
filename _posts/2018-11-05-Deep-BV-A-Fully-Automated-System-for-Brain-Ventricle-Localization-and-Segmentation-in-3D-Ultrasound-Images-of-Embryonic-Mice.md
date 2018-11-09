---
layout: post
title: "Deep BV: A Fully Automated System for Brain Ventricle Localization and Segmentation in 3D Ultrasound Images of Embryonic Mice"
date: 2018-11-05 20:07:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Ziming Qiu, Jack Langerman, Nitin Nair, Orlando Aristizabal, Jonathan Mamou, Daniel H. Turnbull, Jeffrey Ketterling, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric analysis of brain ventricle (BV) structure is a key tool in the study of central nervous system development in embryonic mice. High-frequency ultrasound (HFU) is the only non-invasive, real-time modality available for rapid volumetric imaging of embryos in utero. However, manual segmentation of the BV from HFU volumes is tedious, time-consuming, and requires specialized expertise. In this paper, we propose a novel deep learning based BV segmentation system for whole-body HFU images of mouse embryos. Our fully automated system consists of two modules: localization and segmentation. It first applies a volumetric convolutional neural network on a 3D sliding window over the entire volume to identify a 3D bounding box containing the entire BV. It then employs a fully convolutional network to segment the detected bounding box into BV and background. The system achieves a Dice Similarity Coefficient (DSC) of 0.8956 for BV segmentation on an unseen 111 HFU volume test set surpassing the previous state-of-the-art method (DSC of 0.7119) by a margin of 25%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03601](http://arxiv.org/abs/1811.03601)

##### PDF
[http://arxiv.org/pdf/1811.03601](http://arxiv.org/pdf/1811.03601)

