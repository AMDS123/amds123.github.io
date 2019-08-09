---
layout: post
title: "Multi Scale Supervised 3D U-Net for Kidney and Tumor Segmentation"
date: 2019-08-09 02:41:55
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Wenshuai Zhao, Zengfeng Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
U-Net has achieved huge success in various medical image segmentation challenges. Kinds of new architectures with bells and whistles might succeed in certain dataset when employed with optimal hyper-parameter, but their generalization always can't be guaranteed. Here, we focused on the basic U-Net architecture and proposed a multi scale supervised 3D U-Net for the segmentation task in KiTS19 challenge. To enhance the performance, our work can be summarized as three folds: first, we used multi scale supervision in the decoder pathway, which could encourage the network to pre-dict right results from the deep layers; second, with the aim to alleviate the bad effect from the sample imbalance of kidney and tumor, we adopted exponential logarithmic loss; third, a connected-component based post processing method was designed to remove the obviously wrong voxels. In the published KiTS19 training dataset (totally 210 patients), we divided 42 patients to be test dataset and finally obtained DICE scores of 0.969 and 0.805 for the kidney and tumor respectively. In the challenge, we finally achieved the 7th place among 106 teams with the Composite Dice of 0.8961, namely 0.9741 for kidney and 0.8181 for tumor.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03204](http://arxiv.org/abs/1908.03204)

##### PDF
[http://arxiv.org/pdf/1908.03204](http://arxiv.org/pdf/1908.03204)

