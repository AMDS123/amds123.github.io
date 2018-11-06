---
layout: post
title: "Decoupling Respiratory and Angular Variation in Rotational X-ray Scans Using a Prior Bilinear Model"
date: 2018-11-05 09:23:29
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN
author: Tobias Geimer, Paul Keall, Katharina Breininger, Vincent Caillet, Michelle Dunbar, Christoph Bert, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Data-driven respiratory signal extraction from rotational X-ray scans is a challenge as angular effects overlap with respiration-induced change in the scene. In this paper, we use the linearity of the X-ray transform to propose a bilinear model based on a prior 4D scan to separate angular and respiratory variation. The bilinear estimation process is supported by a B-spline interpolation using prior knowledge about the trajectory angle. Consequently, extraction of respiratory features simplifies to a linear problem. Though the need for a prior 4D CT seems steep, our proposed use-case of driving a respiratory motion model in radiation therapy usually meets this requirement. We evaluate on DRRs of 5 patient 4D CTs in a leave-one-phase-out manner and achieve a mean estimation error of 3.01 % in the gray values for unseen viewing angles. We further demonstrate suitability of the extracted weights to drive a motion model for treatments with a continuously rotating gantry.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.11227](http://arxiv.org/abs/1804.11227)

##### PDF
[http://arxiv.org/pdf/1804.11227](http://arxiv.org/pdf/1804.11227)

