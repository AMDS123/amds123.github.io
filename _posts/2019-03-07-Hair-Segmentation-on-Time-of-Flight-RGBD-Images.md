---
layout: post
title: "Hair Segmentation on Time-of-Flight RGBD Images"
date: 2019-03-07 08:55:35
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Yuanxi Ma, Cen Wan, Guli Zhang, Qilei Jiang, Shiying Li, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Robust segmentation of hair from portrait images remains challenging: hair does not conform to a uniform shape, style or even color; dark hair in particular lacks features. We present a novel computational imaging solution that tackles the problem from both input and processing fronts. We explore using Time-of-Flight (ToF) RGBD sensors on recent mobile devices. We first conduct a comprehensive analysis to show that scattering and inter-reflection cause different noise patterns on hair vs. non-hair regions on ToF images, by changing the light path and/or combining multiple paths. We then develop a deep network based approach that employs both ToF depth map and the RGB gradient maps to produce an initial hair segmentation with labeled hair components. We then refine the result by imposing ToF noise prior under the conditional random field. We collect the first ToF RGBD hair dataset with 20k+ head images captured on 30 human subjects with a variety of hairstyles at different view angles. Comprehensive experiments show that our approach outperforms the RGB based techniques in accuracy and robustness and can handle traditionally challenging cases such as dark hair, similar hair/background, similar hair/foreground, etc.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02775](http://arxiv.org/abs/1903.02775)

##### PDF
[http://arxiv.org/pdf/1903.02775](http://arxiv.org/pdf/1903.02775)

