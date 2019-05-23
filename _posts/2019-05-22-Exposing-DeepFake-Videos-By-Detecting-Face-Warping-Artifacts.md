---
layout: post
title: "Exposing DeepFake Videos By Detecting Face Warping Artifacts"
date: 2019-05-22 15:06:39
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning
author: Yuezun Li, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we describe a new deep learning based method that can effectively distinguish AI-generated fake videos (referred to as {\em DeepFake} videos hereafter) from real videos. Our method is based on the observations that current DeepFake algorithm can only generate images of limited resolutions, which need to be further warped to match the original faces in the source video. Such transforms leave distinctive artifacts in the resulting DeepFake videos, and we show that they can be effectively captured by convolutional neural networks (CNNs). Compared to previous methods which use a large amount of real and DeepFake generated images to train CNN classifier, our method does not need DeepFake generated images as negative training examples since we target the artifacts in affine face warping as the distinctive feature to distinguish real and fake images. The advantages of our method are two-fold: (1) Such artifacts can be simulated directly using simple image processing operations on a image to make it as negative example. Since training a DeepFake model to generate negative examples is time-consuming and resource-demanding, our method saves a plenty of time and resources in training data collection; (2) Since such artifacts are general existed in DeepFake videos from different sources, our method is more robust compared to others. Our method is evaluated on two sets of DeepFake video datasets for its effectiveness in practice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00656](http://arxiv.org/abs/1811.00656)

##### PDF
[http://arxiv.org/pdf/1811.00656](http://arxiv.org/pdf/1811.00656)

