---
layout: post
title: "Event-based Camera Pose Tracking using a Generative Event Model"
date: 2015-10-07 14:52:08
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Guillermo Gallego, Christian Forster, Elias Mueggler, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based vision sensors mimic the operation of biological retina and they represent a major paradigm shift from traditional cameras. Instead of providing frames of intensity measurements synchronously, at artificially chosen rates, event-based cameras provide information on brightness changes asynchronously, when they occur. Such non-redundant pieces of information are called "events". These sensors overcome some of the limitations of traditional cameras (response time, bandwidth and dynamic range) but require new methods to deal with the data they output. We tackle the problem of event-based camera localization in a known environment, without additional sensing, using a probabilistic generative event model in a Bayesian filtering framework. Our main contribution is the design of the likelihood function used in the filter to process the observed events. Based on the physical characteristics of the sensor and on empirical evidence of the Gaussian-like distribution of spiked events with respect to the brightness change, we propose to use the contrast residual as a measure of how well the estimated pose of the event-based camera and the environment explain the observed events. The filter allows for localization in the general case of six degrees-of-freedom motions.

##### Abstract (translated by Google)
基于事件的视觉传感器模仿生物视网膜的运作，它们代表了传统相机的一个主要范式转变。基于事件的摄像机不是在人为选择的速率下同步提供强度测量帧，而是在出现异常时提供有关亮度变化的信息。这些非冗余的信息被称为“事件”。这些传感器克服了传统相机的一些限制（响应时间，带宽和动态范围），但需要新的方法来处理他们输出的数据。在一个已知的环境中，我们解决了基于事件的相机定位问题，没有额外的感知，在贝叶斯过滤框架中使用概率生成事件模型。我们的主要贡献是设计滤波器中用来处理观测事件的似然函数。基于传感器的物理特性和加速事件相对于亮度变化的高斯分布的经验证据，我们建议使用对比度残差作为基于事件的相机的估计姿态和环境解释了观察到的事件。该过滤器允许在六自由度运动的一般情况下定位。

##### URL
[https://arxiv.org/abs/1510.01972](https://arxiv.org/abs/1510.01972)

##### PDF
[https://arxiv.org/pdf/1510.01972](https://arxiv.org/pdf/1510.01972)

