---
layout: post
title: "On measuring the iconicity of a face"
date: 2019-03-04 23:16:36
categories: arXiv_CV
tags: arXiv_CV Face
author: Prithviraj Dhar, Carlos D. Castillo, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
For a given identity in a face dataset, there are certain iconic images which are more representative of the subject than others. In this paper, we explore the problem of computing the iconicity of a face. The premise of the proposed approach is as follows: For an identity containing a mixture of iconic and non iconic images, if a given face cannot be successfully matched with any other face of the same identity, then the iconicity of the face image is low. Using this information, we train a Siamese Multi-Layer Perceptron network, such that each of its twins predict iconicity scores of the image feature pair, fed in as input. We observe the variation of the obtained scores with respect to covariates such as blur, yaw, pitch, roll and occlusion to demonstrate that they effectively predict the quality of the image and compare it with other existing metrics. Furthermore, we use these scores to weight features for template-based face verification and compare it with media averaging of features.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01581](https://arxiv.org/abs/1903.01581)

##### PDF
[https://arxiv.org/pdf/1903.01581](https://arxiv.org/pdf/1903.01581)

