---
layout: post
title: "LapTool-Net: A Contextual Detector of Surgical Tools in Laparoscopic Videos Based on Recurrent Convolutional Neural Networks"
date: 2019-05-22 06:55:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN RNN Classification Prediction Detection Relation
author: Babak Namazi, Ganesh Sankaranarayanan, Venkat Devarajan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new multilabel classifier, called LapTool-Net to detect the presence of surgical tools in each frame of a laparoscopic video. The novelty of LapTool-Net is the exploitation of the correlation among the usage of different tools and, the tools and tasks - namely, the context of the tools' usage. Towards this goal, the pattern in the co-occurrence of the tools is utilized for designing a decision policy for a multilabel classifier based on a Recurrent Convolutional Neural Network (RCNN) architecture to simultaneously extract the spatio-temporal features. In contrast to the previous multilabel classification methods, the RCNN and the decision model are trained in an end-to-end manner using a multitask learning scheme. To overcome the high imbalance and avoid overfitting caused by the lack of variety in the training data, a high down-sampling rate is chosen based on the more frequent combinations. Furthermore, at the post-processing step, the prediction for all the frames of a video are corrected by designing a bi-directional RNN to model the long-term task's order. LapTool-net was trained using a publicly available dataset of laparoscopic cholecystectomy. The results show LapTool-Net outperforms existing methods significantly, even while using fewer training samples and a shallower architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08983](http://arxiv.org/abs/1905.08983)

##### PDF
[http://arxiv.org/pdf/1905.08983](http://arxiv.org/pdf/1905.08983)

