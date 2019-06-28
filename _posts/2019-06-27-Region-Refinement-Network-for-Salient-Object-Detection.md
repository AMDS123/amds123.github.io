---
layout: post
title: "Region Refinement Network for Salient Object Detection"
date: 2019-06-27 05:45:44
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Attention Prediction Detection
author: Zhuotao Tian, Hengshuang Zhao, Michelle Shu, Jiaze Wang, Ruiyu Li, Xiaoyong Shen, Jiaya Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Albeit intensively studied, false prediction and unclear boundaries are still major issues of salient object detection. In this paper, we propose a Region Refinement Network (RRN), which recurrently filters redundant information and explicitly models boundary information for saliency detection. Different from existing refinement methods, we propose a Region Refinement Module (RRM) that optimizes salient region prediction by incorporating supervised attention masks in the intermediate refinement stages. The module only brings a minor increase in model size and yet significantly reduces false predictions from the background. To further refine boundary areas, we propose a Boundary Refinement Loss (BRL) that adds extra supervision for better distinguishing foreground from background. BRL is parameter free and easy to train. We further observe that BRL helps retain the integrity in prediction by refining the boundary. Extensive experiments on saliency detection datasets show that our refinement module and loss bring significant improvement to the baseline and can be easily applied to different frameworks. We also demonstrate that our proposed model generalizes well to portrait segmentation and shadow detection tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11443](http://arxiv.org/abs/1906.11443)

##### PDF
[http://arxiv.org/pdf/1906.11443](http://arxiv.org/pdf/1906.11443)

