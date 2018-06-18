---
layout: post
title: "Learning Front-end Filter-bank Parameters using Convolutional Neural Networks for Abnormal Heart Sound Detection"
date: 2018-06-15 10:33:31
categories: arXiv_AI
tags: arXiv_AI CNN Detection
author: Ahmed Imtiaz Humayun, Shabnam Ghaffarzadegan, Zhe Feng, Taufiq Hasan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic heart sound abnormality detection can play a vital role in the early diagnosis of heart diseases, particularly in low-resource settings. The state-of-the-art algorithms for this task utilize a set of Finite Impulse Response (FIR) band-pass filters as a front-end followed by a Convolutional Neural Network (CNN) model. In this work, we propound a novel CNN architecture that integrates the front-end bandpass filters within the network using time-convolution (tConv) layers, which enables the FIR filter-bank parameters to become learnable. Different initialization strategies for the learnable filters, including random parameters and a set of predefined FIR filter-bank coefficients, are examined. Using the proposed tConv layers, we add constraints to the learnable FIR filters to ensure linear and zero phase responses. Experimental evaluations are performed on a balanced 4-fold cross-validation task prepared using the PhysioNet/CinC 2016 dataset. Results demonstrate that the proposed models yield superior performance compared to the state-of-the-art system, while the linear phase FIR filterbank method provides an absolute improvement of 9.54% over the baseline in terms of an overall accuracy metric.

##### Abstract (translated by Google)
自动心音异常检测可以在心脏疾病的早期诊断中发挥重要作用，特别是在资源匮乏的环境中。该任务的最新算法利用一组有限脉冲响应（FIR）带通滤波器作为前端，然后是卷积神经网络（CNN）模型。在这项工作中，我们提出了一种新颖的CNN架构，它使用时间卷积（tConv）层集成了网络内的前端带通滤波器，使FIR滤波器组参数变得可学。检查可学习滤波器的不同初始化策略，包括随机参数和一组预定义的FIR滤波器组系数。使用提出的tConv层，我们为可学习的FIR滤波器添加约束条件，以确保线性和零相位响应。实验评估是在使用PhysioNet / CinC 2016数据集准备的平衡4倍交叉验证任务上执行的。结果表明，与最先进的系统相比，所提出的模型产生优越的性能，而线性相位FIR滤波器组方法在整体精度度量方面比基线提供了9.54％的绝对改进。

##### URL
[http://arxiv.org/abs/1806.05892](http://arxiv.org/abs/1806.05892)

##### PDF
[http://arxiv.org/pdf/1806.05892](http://arxiv.org/pdf/1806.05892)

