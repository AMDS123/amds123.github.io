---
layout: post
title: "A Deep Regression Model for Seed Identification in Prostate Brachytherapy"
date: 2019-06-24 19:17:37
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yading Yuan, Ren-Dih Sheu, Luke Fu, Yeh-Chi Lo
mathjax: true
---

* content
{:toc}

##### Abstract
Post-implant dosimetry (PID) is an essential step of prostate brachytherapy that utilizes CT to image the prostate and allow the location and dose distribution of the radioactive seeds to be directly related to the actual prostate. However, it it a very challenging task to identify these seeds in CT images due to the severe metal artifacts and high-overlapped appearance when multiple seeds clustered together. In this paper, we propose an automatic and efficient algorithm based on 3D deep fully convolutional network for identifying implanted seeds in CT images. Our method models the seed localization task as a supervised regression problem that projects the input CT image to a map where each element represents the probability that the corresponding input voxel belongs to a seed. This deep regression model significantly suppresses image artifacts and makes the post-processing much easier and more controllable. The proposed method is validated on a large clinical database with 7820 seeds in 100 patients, in which 5534 seeds from 70 patients were used for model training and validation. Our method correctly detected 2150 of 2286 (94.1%) seeds in the 30 testing patients, yielding 16% improvement as compared to a widely-used commercial seed finder software (VariSeed, Varian, Palo Alto, CA).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10183](http://arxiv.org/abs/1906.10183)

##### PDF
[http://arxiv.org/pdf/1906.10183](http://arxiv.org/pdf/1906.10183)

