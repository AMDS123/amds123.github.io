---
layout: post
title: "Recurrent Calibration Network for Irregular Text Recognition"
date: 2018-12-18 02:56:17
categories: arXiv_CV
tags: arXiv_CV Attention Recognition
author: Yunze Gao, Yingying Chen, Jinqiao Wang, Zhen Lei, Xiao-Yu Zhang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text recognition has received increased attention in the research community. Text in the wild often possesses irregular arrangements, typically including perspective text, curved text, oriented text. Most existing methods are hard to work well for irregular text, especially for severely distorted text. In this paper, we propose a novel Recurrent Calibration Network (RCN) for irregular scene text recognition. The RCN progressively calibrates the irregular text to boost the recognition performance. By decomposing the calibration process into multiple steps, the irregular text can be calibrated to normal one step by step. Besides, in order to avoid the accumulation of lost information caused by inaccurate transformation, we further design a fiducial-point refinement structure to keep the integrity of text during the recurrent process. Instead of the calibrated images, the coordinates of fiducial points are tracked and refined, which implicitly models the transformation information. Based on the refined fiducial points, we estimate the transformation parameters and sample from the original image at each step. In this way, the original character information is preserved until the final transformation. Such designs lead to optimal calibration results to boost the performance of succeeding recognition. Extensive experiments on challenging datasets demonstrate the superiority of our method, especially on irregular benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07145](http://arxiv.org/abs/1812.07145)

##### PDF
[http://arxiv.org/pdf/1812.07145](http://arxiv.org/pdf/1812.07145)

