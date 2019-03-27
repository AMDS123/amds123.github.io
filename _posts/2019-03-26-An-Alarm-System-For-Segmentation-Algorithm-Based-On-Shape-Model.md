---
layout: post
title: "An Alarm System For Segmentation Algorithm Based On Shape Model"
date: 2019-03-26 00:55:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Fengze Liu, Yingda Xia, Dong Yang, Alana Yuille, Daguang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
It is usually hard for a learning system to predict correctly on rare events that never occur in the training data, and there is no exception for segmentation algorithms. Meanwhile, manual inspection of each case to locate the failures becomes infeasible due to the trend of large data scale and limited human resource.Therefore, we build an alarm system that will set off alerts when the segmentation result is possibly unsatisfactory, assuming no corresponding ground truth mask is provided. One plausible solution is to project the segmentation results into a low dimensional feature space; then learn classifiers/regressors to predict their qualities. Motivated by this, in this paper, we learn a feature space using the shape information which is a strong prior shared among different datasets and robust to the appearance variation of input data.The shape feature is captured using a Variational Auto-Encoder (VAE) network that trained with only the ground truth masks. During testing, the segmentation results with bad shapes shall not fit the shape prior well, resulting in large loss values. Thus, the VAE is able to evaluate the quality of segmentation result on unseen data, without using ground truth. Finally, we learn a regressor in the one-dimensional feature space to predict the qualities of segmentation results. Our alarm system is evaluated on several recent state-of-art segmentation algorithms for 3D medical segmentation tasks. Compared with other standard quality assessment methods, our system consistently provides more reliable prediction on the qualities of segmentation results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10645](http://arxiv.org/abs/1903.10645)

##### PDF
[http://arxiv.org/pdf/1903.10645](http://arxiv.org/pdf/1903.10645)

