---
layout: post
title: "Automated Segmentation of Hip and Thigh Muscles in Metal Artifact-Contaminated CT using Convolutional Neural Network-Enhanced Normalized Metal Artifact Reduction"
date: 2019-06-27 08:06:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN
author: Mitsuki Sakamoto, Yuta Hiasa, Yoshito Otake, Masaki Takao, Yuki Suzuki, Nobuhiko Sugano, Yoshinobu Sato
mathjax: true
---

* content
{:toc}

##### Abstract
In total hip arthroplasty, analysis of postoperative medical images is important to evaluate surgical outcome. Since Computed Tomography (CT) is most prevalent modality in orthopedic surgery, we aimed at the analysis of CT image. In this work, we focus on the metal artifact in postoperative CT caused by the metallic implant, which reduces the accuracy of segmentation especially in the vicinity of the implant. Our goal was to develop an automated segmentation method of the bones and muscles in the postoperative CT images. We propose a method that combines Normalized Metal Artifact Reduction (NMAR), which is one of the state-of-the-art metal artifact reduction methods, and a Convolutional Neural Network-based segmentation using two U-net architectures. The first U-net refines the result of NMAR and the muscle segmentation is performed by the second U-net. We conducted experiments using simulated images of 20 patients and real images of three patients to evaluate the segmentation accuracy of 19 muscles. In simulation study, the proposed method showed statistically significant improvement (p&lt;0.05) in the average symmetric surface distance (ASD) metric for 14 muscles out of 19 muscles and the average ASD of all muscles from 1.17 +/- 0.543 mm (mean +/- std over all patients) to 1.10 +/- 0.509 mm over our previous method. The real image study using the manual trace of gluteus maximus and medius muscles showed ASD of 1.32 +/- 0.25 mm. Our future work includes training of a network in an end-to-end manner for both the metal artifact reduction and muscle segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11484](http://arxiv.org/abs/1906.11484)

##### PDF
[http://arxiv.org/pdf/1906.11484](http://arxiv.org/pdf/1906.11484)

