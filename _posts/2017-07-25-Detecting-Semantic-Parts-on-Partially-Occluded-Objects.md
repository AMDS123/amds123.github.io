---
layout: post
title: "Detecting Semantic Parts on Partially Occluded Objects"
date: 2017-07-25 05:54:01
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jianyu Wang, Cihang Xie, Zhishuai Zhang, Jun Zhu, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the task of detecting semantic parts on partially occluded objects. We consider a scenario where the model is trained using non-occluded images but tested on occluded images. The motivation is that there are infinite number of occlusion patterns in real world, which cannot be fully covered in the training data. So the models should be inherently robust and adaptive to occlusions instead of fitting / learning the occlusion patterns in the training data. Our approach detects semantic parts by accumulating the confidence of local visual cues. Specifically, the method uses a simple voting method, based on log-likelihood ratio tests and spatial constraints, to combine the evidence of local cues. These cues are called visual concepts, which are derived by clustering the internal states of deep networks. We evaluate our voting scheme on the VehicleSemanticPart dataset with dense part annotations. We randomly place two, three or four irrelevant objects onto the target object to generate testing images with various occlusions. Experiments show that our algorithm outperforms several competitors in semantic part detection when occlusions are present.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.07819](https://arxiv.org/abs/1707.07819)

##### PDF
[https://arxiv.org/pdf/1707.07819](https://arxiv.org/pdf/1707.07819)

