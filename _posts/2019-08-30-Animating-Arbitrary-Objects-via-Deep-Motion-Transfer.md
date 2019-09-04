---
layout: post
title: "Animating Arbitrary Objects via Deep Motion Transfer"
date: 2019-08-30 23:48:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Deep_Learning Prediction Detection
author: Aliaksandr Siarohin, St&#xe9;phane Lathuili&#xe8;re, Sergey Tulyakov, Elisa Ricci, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel deep learning framework for image animation. Given an input image with a target object and a driving video sequence depicting a moving object, our framework generates a video in which the target object is animated according to the driving sequence. This is achieved through a deep architecture that decouples appearance and motion information. Our framework consists of three main modules: (i) a Keypoint Detector unsupervisely trained to extract object keypoints, (ii) a Dense Motion prediction network for generating dense heatmaps from sparse keypoints, in order to better encode motion information and (iii) a Motion Transfer Network, which uses the motion heatmaps and appearance information extracted from the input image to synthesize the output frames. We demonstrate the effectiveness of our method on several benchmark datasets, spanning a wide variety of object appearances, and show that our approach outperforms state-of-the-art image animation and video generation methods. Our source code is publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08861](http://arxiv.org/abs/1812.08861)

##### PDF
[http://arxiv.org/pdf/1812.08861](http://arxiv.org/pdf/1812.08861)

