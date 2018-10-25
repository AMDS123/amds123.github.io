---
layout: post
title: "Coarse-to-fine volumetric segmentation of teeth in Cone-Beam CT"
date: 2018-10-24 11:07:44
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation
author: Matvey Ezhov, Adel Zakirov, Maxim Gusarev
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of localizing and segmenting individual teeth inside 3D Cone-Beam Computed Tomography (CBCT) images. To handle large image sizes we approach this task with a coarse-to-fine framework, where the whole volume is first analyzed as a 33-class semantic segmentation (adults have up to 32 teeth) in coarse resolution, followed by binary semantic segmentation of the cropped region of interest in original resolution. To improve the performance of the challenging 33-class segmentation, we first train the Coarse step model on a large weakly labeled dataset, then fine-tune it on a smaller precisely labeled dataset. The Fine step model is trained with precise labels only. Experiments using our in-house dataset show significant improvement for both weakly-supervised pretraining and for the addition of the Fine step. Empirically, this framework yields precise teeth masks with low localization errors sufficient for many real-world applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10293](http://arxiv.org/abs/1810.10293)

##### PDF
[http://arxiv.org/pdf/1810.10293](http://arxiv.org/pdf/1810.10293)

