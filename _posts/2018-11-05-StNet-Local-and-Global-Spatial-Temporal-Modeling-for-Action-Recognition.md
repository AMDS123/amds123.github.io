---
layout: post
title: "StNet: Local and Global Spatial-Temporal Modeling for Action Recognition"
date: 2018-11-05 08:30:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption Action_Recognition RNN Deep_Learning Relation Recognition
author: Dongliang He, Zhichao Zhou, Chuang Gan, Fu Li, Xiao Liu, Yandong Li, Liming Wang, Shilei Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of deep learning for static image understanding, it remains unclear what are the most effective network architectures for the spatial-temporal modeling in videos. In this paper, in contrast to the existing CNN+RNN or pure 3D convolution based approaches, we explore a novel spatial temporal network (StNet) architecture for both local and global spatial-temporal modeling in videos. Particularly, StNet stacks N successive video frames into a \emph{super-image} which has 3N channels and applies 2D convolution on super-images to capture local spatial-temporal relationship. To model global spatial-temporal relationship, we apply temporal convolution on the local spatial-temporal feature maps. Specifically, a novel temporal Xception block is proposed in StNet. It employs a separate channel-wise and temporal-wise convolution over the feature sequence of video. Extensive experiments on the Kinetics dataset demonstrate that our framework outperforms several state-of-the-art approaches in action recognition and can strike a satisfying trade-off between recognition accuracy and model complexity. We further demonstrate the generalization performance of the leaned video representations on the UCF101 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01549](http://arxiv.org/abs/1811.01549)

##### PDF
[http://arxiv.org/pdf/1811.01549](http://arxiv.org/pdf/1811.01549)

