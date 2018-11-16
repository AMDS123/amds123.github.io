---
layout: post
title: "A multi-level convolutional LSTM model for the segmentation of left ventricle myocardium in infarcted porcine cine MR images"
date: 2018-11-14 20:37:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN
author: Dongqing Zhang, Ilknur Icke, Belma Dogdas, Sarayu Parimal, Smita Sampath, Joseph Forbes, Ansuman Bagchi, Chih-Liang Chin, Antong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of left ventricle (LV) myocardium in cardiac short-axis cine MR images acquired on subjects with myocardial infarction is a challenging task, mainly because of the various types of image inhomogeneity caused by the infarctions. Among the approaches proposed to automate the LV myocardium segmentation task, methods based upon deep convolutional neural networks (CNN) have demonstrated their exceptional accuracy and robustness in recent years. However, most of the CNN-based approaches treat the frames in a cardiac cycle independently, which fails to capture the valuable dynamics of heart motion. Herein, an approach based on recurrent neural network (RNN), specifically a multi-level convolutional long short-term memory (ConvLSTM) model, is proposed to take the motion of the heart into consideration. Based on a ResNet-56 CNN, LV-related image features in consecutive frames of a cardiac cycle are extracted at both the low- and high-resolution levels, which are processed by the corresponding multi-level ConvLSTM models to generate the myocardium segmentations. A leave-one-out experiment was carried out on a set of 3,600 cardiac cine MR slices collected in-house for 8 porcine subjects with surgically induced myocardial infarction. Compared with a solely CNN-based approach, the proposed approach demonstrated its superior robustness against image inhomogeneity by incorporating information from adjacent frames. It also outperformed a one-level ConvLSTM approach thanks to its capabilities to take advantage of image features at multiple resolution levels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06051](http://arxiv.org/abs/1811.06051)

##### PDF
[http://arxiv.org/pdf/1811.06051](http://arxiv.org/pdf/1811.06051)

