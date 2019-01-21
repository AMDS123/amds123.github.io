---
layout: post
title: "Backbone Can Not be Trained at Once: Rolling Back to Pre-trained Network for Person Re-Identification"
date: 2019-01-18 09:08:53
categories: arXiv_CV
tags: arXiv_CV Re-identification Segmentation Pose_Estimation Person_Re-identification CNN Classification
author: Youngmin Ro, Jongwon Choi, Dae Ung Jo, Byeongho Heo, Jongin Lim, Jin Young Choi
mathjax: true
---

* content
{:toc}

##### Abstract
In person re-identification (ReID) task, because of its shortage of trainable dataset, it is common to utilize fine-tuning method using a classification network pre-trained on a large dataset. However, it is relatively difficult to sufficiently fine-tune the low-level layers of the network due to the gradient vanishing problem. In this work, we propose a novel fine-tuning strategy that allows low-level layers to be sufficiently trained by rolling back the weights of high-level layers to their initial pre-trained weights. Our strategy alleviates the problem of gradient vanishing in low-level layers and robustly trains the low-level layers to fit the ReID dataset, thereby increasing the performance of ReID tasks. The improved performance of the proposed strategy is validated via several experiments. Furthermore, without any add-ons such as pose estimation or segmentation, our strategy exhibits state-of-the-art performance using only vanilla deep convolutional neural network architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06140](http://arxiv.org/abs/1901.06140)

##### PDF
[http://arxiv.org/pdf/1901.06140](http://arxiv.org/pdf/1901.06140)

