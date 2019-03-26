---
layout: post
title: "Residual Pyramid Learning for Single-Shot Semantic Segmentation"
date: 2019-03-23 02:48:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction
author: Xiaoyu Chen, Xiaotian Lou, Lianfa Bai, Jing Han
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-level semantic segmentation is a challenging task with a huge amount of computation, especially if the size of input is large. In the segmentation model, apart from the feature extraction, the extra decoder structure is often employed to recover spatial information. In this paper, we put forward a method for single-shot segmentation in a feature residual pyramid network (RPNet), which learns the main and residuals of segmentation by decomposing the label at different levels of residual blocks. Specifically speaking, we use the residual features to learn the edges and details, and the identity features to learn the main part of targets. At testing time, the predicted residuals are used to enhance the details of the top-level prediction. Residual learning blocks split the network into several shallow sub-networks which facilitates the training of the RPNet. We then evaluate the proposed method and compare it with recent state-of-the-art methods on CamVid and Cityscapes. The proposed single-shot segmentation based on RPNet achieves impressive results with high efficiency on pixel-level segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09746](http://arxiv.org/abs/1903.09746)

##### PDF
[http://arxiv.org/pdf/1903.09746](http://arxiv.org/pdf/1903.09746)

