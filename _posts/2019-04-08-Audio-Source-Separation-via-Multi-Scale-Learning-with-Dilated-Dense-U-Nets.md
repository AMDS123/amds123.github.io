---
layout: post
title: "Audio Source Separation via Multi-Scale Learning with Dilated Dense U-Nets"
date: 2019-04-08 16:13:16
categories: arXiv_SD
tags: arXiv_SD
author: Vivek Sivaraman Narayanaswamy, Sameeksha Katoch, Jayaraman J. Thiagarajan, Huan Song, Andreas Spanias
mathjax: true
---

* content
{:toc}

##### Abstract
Modern audio source separation techniques rely on optimizing sequence model architectures such as, 1D-CNNs, on mixture recordings to generalize well to unseen mixtures. Specifically, recent focus is on time-domain based architectures such as Wave-U-Net which exploit temporal context by extracting multi-scale features. However, the optimality of the feature extraction process in these architectures has not been well investigated. In this paper, we examine and recommend critical architectural changes that forge an optimal multi-scale feature extraction process. To this end, we replace regular $1-$D convolutions with adaptive dilated convolutions that have innate capability of capturing increased context by using large temporal receptive fields. We also investigate the impact of dense connections on the extraction process that encourage feature reuse and better gradient flow. The dense connections between the downsampling and upsampling paths of a U-Net architecture capture multi-resolution information leading to improved temporal modelling. We evaluate the proposed approaches on the MUSDB test dataset. In addition to providing an improved performance over the state-of-the-art, we also provide insights on the impact of different architectural choices on complex data-driven solutions for source separation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04161](http://arxiv.org/abs/1904.04161)

##### PDF
[http://arxiv.org/pdf/1904.04161](http://arxiv.org/pdf/1904.04161)

