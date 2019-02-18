---
layout: post
title: "Improving Catheter Segmentation & Localization in 3D Cardiac Ultrasound Using Direction-Fused FCN"
date: 2019-02-14 19:57:14
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Detection
author: Hongxu Yang, Caifeng Shan, Alexander F. Kolen, Peter H.N. de With
mathjax: true
---

* content
{:toc}

##### Abstract
Fast and accurate catheter detection in cardiac catheterization using harmless 3D ultrasound (US) can improve the efficiency and outcome of the intervention. However, the low image quality of US requires extra training for sonographers to localize the catheter. In this paper, we propose a catheter detection method based on a pre-trained VGG network, which exploits 3D information through re-organized cross-sections to segment the catheter by a shared fully convolutional network (FCN), which is called a Direction-Fused FCN (DF-FCN). Based on the segmented image of DF-FCN, the catheter can be localized by model fitting. Our experiments show that the proposed method can successfully detect an ablation catheter in a challenging ex-vivo 3D US dataset, which was collected on the porcine heart. Extensive analysis shows that the proposed method achieves a Dice score of 57.7%, which offers at least an 11.8 % improvement when compared to state-of-the-art instrument detection methods. Due to the improved segmentation performance by the DF-FCN, the catheter can be localized with an error of only 1.4 mm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05582](http://arxiv.org/abs/1902.05582)

##### PDF
[http://arxiv.org/pdf/1902.05582](http://arxiv.org/pdf/1902.05582)

