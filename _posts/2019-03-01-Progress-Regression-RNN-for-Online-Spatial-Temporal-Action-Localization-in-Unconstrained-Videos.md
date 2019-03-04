---
layout: post
title: "Progress Regression RNN for Online Spatial-Temporal Action Localization in Unconstrained Videos"
date: 2019-03-01 14:08:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN RNN Detection Relation
author: Bo Hu, Jianfei Cai, Tat-Jen Cham, Junsong Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Previous spatial-temporal action localization methods commonly follow the pipeline of object detection to estimate bounding boxes and labels of actions. However, the temporal relation of an action has not been fully explored. In this paper, we propose an end-to-end Progress Regression Recurrent Neural Network (PR-RNN) for online spatial-temporal action localization, which learns to infer the action by temporal progress regression. Two new action attributes, called progression and progress rate, are introduced to describe the temporal engagement and relative temporal position of an action. In our method, frame-level features are first extracted by a Fully Convolutional Network (FCN). Subsequently, detection results and action progress attributes are regressed by the Convolutional Gated Recurrent Unit (ConvGRU) based on all the observed frames instead of a single frame or a short clip. Finally, a novel online linking method is designed to connect single-frame results to spatial-temporal tubes with the help of the estimated action progress attributes. Extensive experiments demonstrate that the progress attributes improve the localization accuracy by providing more precise temporal position of an action in unconstrained videos. Our proposed PR-RNN achieves the stateof-the-art performance for most of the IoU thresholds on two benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00304](http://arxiv.org/abs/1903.00304)

##### PDF
[http://arxiv.org/pdf/1903.00304](http://arxiv.org/pdf/1903.00304)

