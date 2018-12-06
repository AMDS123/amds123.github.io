---
layout: post
title: "Few-shot Object Detection via Feature Reweighting"
date: 2018-12-05 09:23:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Bingyi Kang, Zhuang Liu, Xin Wang, Fisher Yu, Jiashi Feng, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
This work aims to solve the challenging few-shot object detection problem where only a few annotated examples are available for each object category to train a detection model. Such an ability of learning to detect an object from just a few examples is common for human vision systems, but remains absent for computer vision systems. Though few-shot meta learning offers a promising solution technique, previous works mostly target the task of image classification and are not directly applicable for the much more complicated object detection task. In this work, we propose a novel meta-learning based model with carefully designed architecture, which consists of a meta-model and a base detection model. The base detection model is trained on several base classes with sufficient samples to offer basis features. The meta-model is trained to reweight importance of features from the base detection model over the input image and adapt these features to assist novel object detection from a few examples. The meta-model is light-weight, end-to-end trainable and able to entail the base model with detection ability for novel objects fast. Through experiments we demonstrated our model can outperform baselines by a large margin for few-shot object detection, on multiple datasets and settings. Our model also exhibits fast adaptation speed to novel few-shot classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01866](http://arxiv.org/abs/1812.01866)

##### PDF
[http://arxiv.org/pdf/1812.01866](http://arxiv.org/pdf/1812.01866)

