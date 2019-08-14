---
layout: post
title: "NeuroMask: Explaining Predictions of Deep Neural Networks through Mask Learning"
date: 2019-08-05 07:33:30
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Prediction Recognition
author: Moustafa Alzantot, Amy Widdicombe, Simon Julier, Mani Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) deliver state-of-the-art performance in many image recognition and understanding applications. However, despite their outstanding performance, these models are black-boxes and it is hard to understand how they make their decisions. Over the past few years, researchers have studied the problem of providing explanations of why DNNs predicted their results. However, existing techniques are either obtrusive, requiring changes in model training, or suffer from low output quality. In this paper, we present a novel method, NeuroMask, for generating an interpretable explanation of classification model results. When applied to image classification models, NeuroMask identifies the image parts that are most important to classifier results by applying a mask that hides/reveals different parts of the image, before feeding it back into the model. The mask values are tuned by minimizing a properly designed cost function that preserves the classification result and encourages producing an interpretable mask. Experiments using state-of-the-art Convolutional Neural Networks for image recognition on different datasets (CIFAR-10 and ImageNet) show that NeuroMask successfully localizes the parts of the input image which are most relevant to the DNN decision. By showing a visual quality comparison between NeuroMask explanations and those of other methods, we find NeuroMask to be both accurate and interpretable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04389](http://arxiv.org/abs/1908.04389)

##### PDF
[http://arxiv.org/pdf/1908.04389](http://arxiv.org/pdf/1908.04389)

