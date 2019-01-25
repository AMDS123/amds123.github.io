---
layout: post
title: "Using CycleGANs for effectively reducing image variability across OCT devices and improving retinal fluid segmentation"
date: 2019-01-24 12:37:14
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Philipp Seeb&#xf6;ck, David Romo-Bucheli, Sebastian Waldstein, Hrvoje Bogunovi&#x107;, Jos&#xe9; Ignacio Orlando, Bianca S. Gerendas, Georg Langs, Ursula Schmidt-Erfurth
mathjax: true
---

* content
{:toc}

##### Abstract
Optical coherence tomography (OCT) has become the most important imaging modality in ophthalmology. A substantial amount of research has recently been devoted to the development of machine learning (ML) models for the identification and quantification of pathological features in OCT images. Among the several sources of variability the ML models have to deal with, a major factor is the acquisition device, which can limit the ML model's generalizability. In this paper, we propose to reduce the image variability across different OCT devices (Spectralis and Cirrus) by using CycleGAN, an unsupervised unpaired image transformation algorithm. The usefulness of this approach is evaluated in the setting of retinal fluid segmentation, namely intraretinal cystoid fluid (IRC) and subretinal fluid (SRF). First, we train a segmentation model on images acquired with a source OCT device. Then we evaluate the model on (1) source, (2) target and (3) transformed versions of the target OCT images. The presented transformation strategy shows an F1 score of 0.4 (0.51) for IRC (SRF) segmentations. Compared with traditional transformation approaches, this means an F1 score gain of 0.2 (0.12).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08379](http://arxiv.org/abs/1901.08379)

##### PDF
[http://arxiv.org/pdf/1901.08379](http://arxiv.org/pdf/1901.08379)

