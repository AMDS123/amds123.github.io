---
layout: post
title: "Where computer vision can aid physics: dynamic cloud motion forecasting from satellite images"
date: 2017-09-30 12:55:13
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Sergiy Zhuk, Tigran Tchrakian, Albert Akhriev, Siyuan Lu, Hendrik Hamann
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a new algorithm for solar energy forecasting from a sequence of Cloud Optical Depth (COD) images. The algorithm is based on the following simple observation: the dynamics of clouds represented by COD images resembles the motion (transport) of a density in a fluid flow. This suggests that, to forecast the motion of COD images, it is sufficient to forecast the flow. The latter, in turn, can be accomplished by fitting a parametric model of the fluid flow to the COD images observed in the past. Namely, the learning phase of the algorithm is composed of the following steps: (i) given a sequence of COD images, the snapshots of the optical flow are estimated from two consecutive COD images; (ii) these snapshots are then assimilated into a Navier-Stokes Equation (NSE), i.e. an initial velocity field for NSE is selected so that the corresponding NSE' solution is as close as possible to the optical flow snapshots. The prediction phase consists of utilizing a linear transport equation, which describes the propagation of COD images in the fluid flow predicted by NSE, to estimate the future motion of the COD images. The algorithm has been tested on COD images provided by two geostationary operational environmental satellites from NOAA serving the west-hemisphere.

##### Abstract (translated by Google)
本文描述了一个新的算法从太阳能预测从一系列的云光学深度（COD）图像。该算法基于以下简单的观察：由COD图像表示的云的动力学类似于流体流动中密度的运动（运输）。这表明，为了预测COD图像的运动，预测流量就足够了。后者又可以通过将流体流动的参数模型拟合到过去观察到的COD图像来完成。即，算法的学习阶段由以下步骤组成：（i）给出一系列COD图像，从两个连续的COD图像估计光流的快照; （ii）然后将这些快照同化为Navier-Stokes方程（NSE），即，选择用于NSE的初始速度场，使得相应的NSE的解决方案尽可能接近光流快照。预测阶段包括利用描述COD图像在NSE预测的流体流动中的传播的线性输运方程来估计COD图像的未来运动。该算法已经在西半球的NOAA两颗对地静止运行环境卫星提供的COD图像上进行了测试。

##### URL
[https://arxiv.org/abs/1710.00194](https://arxiv.org/abs/1710.00194)

##### PDF
[https://arxiv.org/pdf/1710.00194](https://arxiv.org/pdf/1710.00194)

