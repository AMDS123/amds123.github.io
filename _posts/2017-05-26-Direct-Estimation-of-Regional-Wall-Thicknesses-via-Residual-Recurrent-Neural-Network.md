---
layout: post
title: "Direct Estimation of Regional Wall Thicknesses via Residual Recurrent Neural Network"
date: 2017-05-26 22:04:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN RNN
author: Wufeng Xue, Ilanit Ben Nachum, Sachin Pandey, James Warrington, Stephanie Leung, Shuo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate estimation of regional wall thicknesses (RWT) of left ventricular (LV) myocardium from cardiac MR sequences is of significant importance for identification and diagnosis of cardiac disease. Existing RWT estimation still relies on segmentation of LV myocardium, which requires strong prior information and user interaction. No work has been devoted into direct estimation of RWT from cardiac MR images due to the diverse shapes and structures for various subjects and cardiac diseases, as well as the complex regional deformation of LV myocardium during the systole and diastole phases of the cardiac cycle. In this paper, we present a newly proposed Residual Recurrent Neural Network (ResRNN) that fully leverages the spatial and temporal dynamics of LV myocardium to achieve accurate frame-wise RWT estimation. Our ResRNN comprises two paths: 1) a feed forward convolution neural network (CNN) for effective and robust CNN embedding learning of various cardiac images and preliminary estimation of RWT from each frame itself independently, and 2) a recurrent neural network (RNN) for further improving the estimation by modeling spatial and temporal dynamics of LV myocardium. For the RNN path, we design for cardiac sequences a Circle-RNN to eliminate the effect of null hidden input for the first time-step. Our ResRNN is capable of obtaining accurate estimation of cardiac RWT with Mean Absolute Error of 1.44mm (less than 1-pixel error) when validated on cardiac MR sequences of 145 subjects, evidencing its great potential in clinical cardiac function assessment.

##### Abstract (translated by Google)
准确估计心脏MR序列的左心室（LV）心肌区域壁厚（RWT）对于心脏疾病的鉴别和诊断具有重要意义。现有的RWT估计仍然依赖于LV心肌的分割，这需要强大的先验信息和用户交互。由于各种受试者和心脏疾病的不同形状和结构以及在心动周期的收缩期和舒张期期间LV心肌的复杂的区域变形，没有工作致力于直接估计来自心脏MR图像的RWT。在本文中，我们提出了一个新提出的残余回馈神经网络（ResRNN），充分利用LV心肌的时空动态，以实现准确的逐帧RWT估计。我们的ResRNN包括两个路径：1）前馈卷积神经网络（CNN），用于各种心脏图像的有效和稳健的CNN嵌入学习以及独立地从每个帧本身初步估计RWT;以及2）递归神经网络（RNN）通过对LV心肌的空间和时间动态进行建模来进一步改善估计。对于RNN路径，我们设计了一个Circle-RNN的心脏序列，以消除第一个时间步的空隐藏输入的影响。我们的ResRNN能够获得精确的心脏RWT估计值，其平均绝对误差为1.44mm（小于1像素误差）在145位受试者的心脏MR序列上进行验证，证明了其在临床心脏功能评估中的巨大潜力。

##### URL
[https://arxiv.org/abs/1705.09728](https://arxiv.org/abs/1705.09728)

##### PDF
[https://arxiv.org/pdf/1705.09728](https://arxiv.org/pdf/1705.09728)

