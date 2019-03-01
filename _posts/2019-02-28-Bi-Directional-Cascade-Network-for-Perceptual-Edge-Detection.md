---
layout: post
title: "Bi-Directional Cascade Network for Perceptual Edge Detection"
date: 2019-02-28 05:35:15
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jianzhong He, Shiliang Zhang, Ming Yang, Yanhu Shan, Tiejun Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Exploiting multi-scale representations is critical to improve edge detection for objects at different scales. To extract edges at dramatically different scales, we propose a Bi-Directional Cascade Network (BDCN) structure, where an individual layer is supervised by labeled edges at its specific scale, rather than directly applying the same supervision to all CNN outputs. Furthermore, to enrich multi-scale representations learned by BDCN, we introduce a Scale Enhancement Module (SEM) which utilizes dilated convolution to generate multi-scale features, instead of using deeper CNNs or explicitly fusing multi-scale edge maps. These new approaches encourage the learning of multi-scale representations in different layers and detect edges that are well delineated by their scales. Learning scale dedicated layers also results in compact network with a fraction of parameters. We evaluate our method on three datasets, i.e., BSDS500, NYUDv2, and Multicue, and achieve ODS Fmeasure of 0.828, 1.3% higher than current state-of-the art on BSDS500. The code has been available at https://github.com/pkuCactus/BDCN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10903](http://arxiv.org/abs/1902.10903)

##### PDF
[http://arxiv.org/pdf/1902.10903](http://arxiv.org/pdf/1902.10903)

