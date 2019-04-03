---
layout: post
title: "Monocular 3D Human Pose Estimation by Generation and Ordinal Ranking"
date: 2019-04-02 10:35:14
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Saurabh Sharma, Pavan Teja Varigonda, Prashast Bindal, Abhishek Sharma, Arjun Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular 3D Human Pose Estimation from static images is a challenging problem, due to the curse of dimensionality and the ill-posed nature of lifting 2D to 3D. In this paper, we propose a Deep Conditional Variational Autoencoder based model that synthesizes diverse 3D pose samples conditioned on the estimated 2D pose. Our experiments reveal that the CVAE generates significantly diverse 3D samples that are consistent with the 2D pose, thereby reducing the ambiguity in lifting from 2D-to-3D. We use two strategies for predicting the final 3D pose - (a) depth-ordering/ordinal relations to score and aggregate the final 3D pose, or OrdinalScore, and (b) with supervision from an Oracle. We report close to state of the art results on two benchmark datasets using OrdinalScore, and state-of-the-art results using the Oracle. We also show our pipeline gives competitive results without paired 3D supervision. We shall make the training and evaluation code available at https://github.com/ssfootball04/generative_pose.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01324](http://arxiv.org/abs/1904.01324)

##### PDF
[http://arxiv.org/pdf/1904.01324](http://arxiv.org/pdf/1904.01324)

