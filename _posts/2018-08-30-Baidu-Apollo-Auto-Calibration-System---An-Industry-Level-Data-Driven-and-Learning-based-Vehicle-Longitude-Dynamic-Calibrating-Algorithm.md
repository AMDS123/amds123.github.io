---
layout: post
title: "Baidu Apollo Auto-Calibration System - An Industry-Level Data-Driven and Learning based Vehicle Longitude Dynamic Calibrating Algorithm"
date: 2018-08-30 06:29:10
categories: arXiv_AI
tags: arXiv_AI
author: Fan Zhu, Lin Ma, Xin Xu, Dingfeng Guo, Xiao Cui, Qi Kong
mathjax: true
---

* content
{:toc}

##### Abstract
For any autonomous driving vehicle, control module determines its road performance and safety, i.e. its precision and stability should stay within a carefully-designed range. Nonetheless, control algorithms require vehicle dynamics (such as longitudinal dynamics) as inputs, which, unfortunately, are obscure to calibrate in real time. As a result, to achieve reasonable performance, most, if not all, research-oriented autonomous vehicles do manual calibrations in a one-by-one fashion. Since manual calibration is not sustainable once entering into mass production stage for industrial purposes, we here introduce a machine-learning based auto-calibration system for autonomous driving vehicles. In this paper, we will show how we build a data-driven longitudinal calibration procedure using machine learning techniques. We first generated offline calibration tables from human driving data. The offline table serves as an initial guess for later uses and it only needs twenty-minutes data collection and process. We then used an online-learning algorithm to appropriately update the initial table (the offline table) based on real-time performance analysis. This longitudinal auto-calibration system has been deployed to more than one hundred Baidu Apollo self-driving vehicles (including hybrid family vehicles and electronic delivery-only vehicles) since April 2018. By August 27, 2018, it had been tested for more than two thousands hours, ten thousands kilometers (6,213 miles) and yet proven to be effective.

##### Abstract (translated by Google)
对于任何自动驾驶车辆，控制模块确定其道路性能和安全性，即其精度和稳定性应保持在精心设计的范围内。尽管如此，控制算法需要车辆动力学（例如纵向动力学）作为输入，遗憾的是，这些输入很难实时校准。因此，为了实现合理的性能，大多数（如果不是全部的话）研究型自动驾驶汽车以一对一的方式进行手动校准。由于手动校准一旦进入工业用途的批量生产阶段就不可持续，我们在此引入基于机器学习的自动驾驶车辆自动校准系统。在本文中，我们将展示如何使用机器学习技术构建数据驱动的纵向校准过程。我们首先从人类驾驶数据生成离线校准表。脱机表用作以后使用的初始猜测，它只需要20分钟的数据收集和处理。然后，我们使用在线学习算法，根据实时性能分析适当更新初始表（离线表）。自2018年4月以来，这种纵向自动校准系统已部署到100多辆百度Apollo自动驾驶车辆（包括混合动力家用车和电子交付车辆）。到2018年8月27日，它已经过两次以上的测试数千小时，数万公里（6,213英里），但事实证明是有效的。

##### URL
[http://arxiv.org/abs/1808.10134](http://arxiv.org/abs/1808.10134)

##### PDF
[http://arxiv.org/pdf/1808.10134](http://arxiv.org/pdf/1808.10134)

