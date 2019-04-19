---
layout: post
title: "No-Reference Quality Assessment of Contrast-Distorted Images using Contrast Enhancement"
date: 2019-04-18 16:36:43
categories: arXiv_CV
tags: arXiv_CV QA
author: Jia Yan, Jie Li, Xin Fu
mathjax: true
---

* content
{:toc}

##### Abstract
No-reference image quality assessment (NR-IQA) aims to measure the image quality without reference image. However, contrast distortion has been overlooked in the current research of NR-IQA. In this paper, we propose a very simple but effective metric for predicting quality of contrast-altered images based on the fact that a high-contrast image is often more similar to its contrast enhanced image. Specifically, we first generate an enhanced image through histogram equalization. We then calculate the similarity of the original image and the enhanced one by using structural-similarity index (SSIM) as the first feature. Further, we calculate the histogram based entropy and cross entropy between the original image and the enhanced one respectively, to gain a sum of 4 features. Finally, we learn a regression module to fuse the aforementioned 5 features for inferring the quality score. Experiments on four publicly available databases validate the superiority and efficiency of the proposed technique.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08879](http://arxiv.org/abs/1904.08879)

##### PDF
[http://arxiv.org/pdf/1904.08879](http://arxiv.org/pdf/1904.08879)

