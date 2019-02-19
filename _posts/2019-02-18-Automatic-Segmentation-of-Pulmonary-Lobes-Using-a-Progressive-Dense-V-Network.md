---
layout: post
title: "Automatic Segmentation of Pulmonary Lobes Using a Progressive Dense V-Network"
date: 2019-02-18 00:37:22
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Abdullah-Al-Zubaer Imran, Ali Hatamizadeh, Shilpa P. Ananth, Xiaowei Ding, Demetri Terzopoulos, Nima Tajbakhsh
mathjax: true
---

* content
{:toc}

##### Abstract
Reliable and automatic segmentation of lung lobes is important for diagnosis, assessment, and quantification of pulmonary diseases. The existing techniques are prohibitively slow, undesirably rely on prior (airway/vessel) segmentation, and/or require user interactions for optimal results. This work presents a reliable, fast, and fully automated lung lobe segmentation based on a progressive dense V-network (PDV-Net). The proposed method can segment lung lobes in one forward pass of the network, with an average runtime of 2 seconds using 1 Nvidia Titan XP GPU, eliminating the need for any prior atlases, lung segmentation or any subsequent user intervention. We evaluated our model using 84 chest CT scans from the LIDC and 154 pathological cases from the LTRC datasets. Our model achieved a Dice score of $0.939 \pm 0.02$ for the LIDC test set and $0.950 \pm 0.01$ for the LTRC test set, significantly outperforming a 2D U-net model and a 3D dense V-net. We further evaluated our model against 55 cases from the LOLA11 challenge, obtaining an average Dice score of 0.935---a performance level competitive to the best performing team with an average score of 0.938. Our extensive robustness analyses also demonstrate that our model can reliably segment both healthy and pathological lung lobes in CT scans from different vendors, and that our model is robust against configurations of CT scan reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06362](http://arxiv.org/abs/1902.06362)

##### PDF
[http://arxiv.org/pdf/1902.06362](http://arxiv.org/pdf/1902.06362)

