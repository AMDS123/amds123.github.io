---
layout: post
title: "Count-ception: Counting by Fully Convolutional Redundant Counting"
date: 2017-07-23 17:36:30
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Joseph Paul Cohen, Genevieve Boucher, Craig A. Glastonbury, Henry Z. Lo, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Counting objects in digital images is a process that should be replaced by machines. This tedious task is time consuming and prone to errors due to fatigue of human annotators. The goal is to have a system that takes as input an image and returns a count of the objects inside and justification for the prediction in the form of object localization. We repose a problem, originally posed by Lempitsky and Zisserman, to instead predict a count map which contains redundant counts based on the receptive field of a smaller regression network. The regression network predicts a count of the objects that exist inside this frame. By processing the image in a fully convolutional way each pixel is going to be accounted for some number of times, the number of windows which include it, which is the size of each window, (i.e., 32x32 = 1024). To recover the true count we take the average over the redundant predictions. Our contribution is redundant counting instead of predicting a density map in order to average over errors. We also propose a novel deep neural network architecture adapted from the Inception family of networks called the Count-ception network. Together our approach results in a 20% relative improvement (2.9 to 2.3 MAE) over the state of the art method by Xie, Noble, and Zisserman in 2016.

##### Abstract (translated by Google)
计算数字图像中的对象是一个应该被机器取代的过程。这种繁琐的任务是耗时的，并且由于人类注释者的疲劳而容易出错。我们的目标是建立一个系统，将图像作为输入，并以对象本地化的形式返回内部对象的计数和预测的合理性。我们把原本由Lempitsky和Zisserman提出的问题放在一个问题上，而不是根据一个较小的回归网络的接受领域来预测一个包含多余计数的计数图。回归网络预测该帧内存在的对象的计数。通过以完全卷积的方式处理图像，每个像素将被计入若干次，包括它的窗口的数量（每个窗口的大小）（即32×32 = 1024）。为了恢复真实的数量，我们取多余的预测平均。我们的贡献是冗余计数，而不是预测密度图，以平均错误。我们还提出了一种新的深度神经网络架构，它是从称为Count-ception网络的初始网络家族中改造而来的。我们的方法与2016年由Xie，Noble和Zisserman的最先进方法相比，相对提高了20％（2.9到2.3 MAE）。

##### URL
[https://arxiv.org/abs/1703.08710](https://arxiv.org/abs/1703.08710)

##### PDF
[https://arxiv.org/pdf/1703.08710](https://arxiv.org/pdf/1703.08710)

