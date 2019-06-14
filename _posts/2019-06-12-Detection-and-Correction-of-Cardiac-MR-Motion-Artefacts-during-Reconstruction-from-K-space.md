---
layout: post
title: "Detection and Correction of Cardiac MR Motion Artefacts during Reconstruction from K-space"
date: 2019-06-12 14:58:31
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Quantitative Detection
author: lkay Oksuz, James Clough, Bram Ruijsink, Esther Puyol-Anton, Aurelien Bustin, Gastao Cruz, Claudia Prieto, Daniel Rueckert, Andrew P. King, Julia A. Schnabel
mathjax: true
---

* content
{:toc}

##### Abstract
In fully sampled cardiac MR (CMR) acquisitions, motion can lead to corruption of k-space lines, which can result in artefacts in the reconstructed images. In this paper, we propose a method to automatically detect and correct motion-related artefacts in CMR acquisitions during reconstruction from k-space data. Our correction method is inspired by work on undersampled CMR reconstruction, and uses deep learning to optimize a data-consistency term for under-sampled k-space reconstruction. Our main methodological contribution is the addition of a detection network to classify motion-corrupted k-space lines to convert the problem of artefact correction to a problem of reconstruction using the data consistency term. We train our network to automatically correct for motion-related artefacts using synthetically corrupted cine CMR k-space data as well as uncorrupted CMR images. Using a test set of 50 2D+time cine CMR datasets from the UK Biobank, we achieve good image quality in the presence of synthetic motion artefacts. We quantitatively compare our method with a variety of techniques for recovering good image quality and showcase better performance compared to state of the art denoising techniques with a PSNR of 37.1. Moreover, we show that our method preserves the quality of uncorrupted images and therefore can be also utilized as a general image reconstruction algorithm.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05695](https://arxiv.org/abs/1906.05695)

##### PDF
[https://arxiv.org/pdf/1906.05695](https://arxiv.org/pdf/1906.05695)

