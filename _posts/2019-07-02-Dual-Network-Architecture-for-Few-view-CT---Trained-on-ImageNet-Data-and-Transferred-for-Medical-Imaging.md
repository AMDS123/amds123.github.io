---
layout: post
title: "Dual Network Architecture for Few-view CT --Trained on ImageNet Data and Transferred for Medical Imaging"
date: 2019-07-02 09:46:27
categories: arXiv_CV
tags: arXiv_CV Attention
author: Huidong Xie, Hongming Shan, Wenxiang Cong, Xiaohua Zhang, Shaohua Liu, Ruola Ning, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
X-ray computed tomography (CT) reconstructs cross-sectional images from projection data. However, ionizing X-ray radiation associated with CT scanning might induce cancer and genetic damage and raises public concerns, and the reduction of radiation dose has attracted major attention. Few-view CT image reconstruction is an important topic to reduce the radiation dose. Recently, data-driven algorithms have shown great potential to solve the few-view CT problem. In this paper, we develop a dual network architecture (DNA) for reconstructing images directly from sinograms. In the proposed DNA method, a point-based fully-connected layer learns the backprojection process requesting significantly less memory than the prior art and with O(C*N*N_c) parameters where N and N_c denote the dimension of reconstructed images and number of projections respectively. C is an adjustable parameter that can be set as low as 1. Our experimental results demonstrate that DNA produces a competitive performance over the other state-of-the-art methods. Interestingly, natural images can be used to pre-train DNA to avoid overfitting when the amount of real patient images is limited.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01262](http://arxiv.org/abs/1907.01262)

##### PDF
[http://arxiv.org/pdf/1907.01262](http://arxiv.org/pdf/1907.01262)

