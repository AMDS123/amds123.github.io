---
layout: post
title: "Monocular Depth Estimation with Augmented Ordinal Depth Relationships"
date: 2019-07-11 02:29:02
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Relation
author: Yuanzhouhan Cao, Tianqi Zhao, Ke Xian, Chunhua Shen, Zhiguo Cao, Shugong Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing algorithms for depth estimation from single monocular images need large quantities of metric groundtruth depths for supervised learning. We show that relative depth can be an informative cue for metric depth estimation and can be easily obtained from vast stereo videos. Acquiring metric depths from stereo videos is sometimes impracticable due to the absence of camera parameters. In this paper, we propose to improve the performance of metric depth estimation with relative depths collected from stereo movie videos using existing stereo matching algorithm. We introduce a new "Relative Depth in Stereo" (RDIS) dataset densely labelled with relative depths. We first pretrain a ResNet model on our RDIS dataset. Then we finetune the model on RGB-D datasets with metric ground-truth depths. During our finetuning, we formulate depth estimation as a classification task. This re-formulation scheme enables us to obtain the confidence of a depth prediction in the form of probability distribution. With this confidence, we propose an information gain loss to make use of the predictions that are close to ground-truth. We evaluate our approach on both indoor and outdoor benchmark RGB-D datasets and achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00585](http://arxiv.org/abs/1806.00585)

##### PDF
[http://arxiv.org/pdf/1806.00585](http://arxiv.org/pdf/1806.00585)

