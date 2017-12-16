---
layout: post
title: "Predicting the dynamics of 2d objects with a deep residual network"
date: 2016-11-24 11:12:52
categories: arXiv_CV
tags: arXiv_CV
author: François Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate how a residual network can learn to predict the dynamics of interacting shapes purely as an image-to-image regression task. With a simple 2d physics simulator, we generate short sequences composed of rectangles put in motion by applying a pulling force at a point picked at random. The network is trained with a quadratic loss to predict the image of the resulting configuration, given the image of the starting configuration and an image indicating the point of grasping. Experiments show that the network learns to predict accurately the resulting image, which implies in particular that (1) it segments rectangles as distinct components, (2) it infers which one contains the grasping point, (3) it models properly the dynamic of a single rectangle, including the torque, (4) it detects and handles collisions to some extent, and (5) it re-synthesizes properly the entire scene with displaced rectangles.

##### Abstract (translated by Google)
我们调查残差网络如何学习如何预测交互形状的动态，纯粹是一个图像到图像的回归任务。通过一个简单的二维物理模拟器，我们生成由长方形组成的短序列，通过在随机选取的点上施加一个拉力来进行运动。网络训练有一个二次损失，以预测所得配置的图像，给出了初始配置的图像和指示抓取点的图像。实验表明，网络学习预测精确的结果图像，这意味着特别是（1）它分割矩形作为不同的组成部分，（2）它推断哪一个包含抓取点，（3）它适当建模的动态包括扭矩的单个矩形，（4）它在一定程度上检测和处理碰撞，以及（5）它适当地重新合成具有移位矩形的整个场景。

##### URL
[https://arxiv.org/abs/1610.04032](https://arxiv.org/abs/1610.04032)

##### PDF
[https://arxiv.org/pdf/1610.04032](https://arxiv.org/pdf/1610.04032)

