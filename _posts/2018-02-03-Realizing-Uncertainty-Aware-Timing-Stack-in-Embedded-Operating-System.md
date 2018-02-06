---
layout: post
title: "Realizing Uncertainty-Aware Timing Stack in Embedded Operating System"
date: 2018-02-03 06:18:56
categories: arXiv_RO
tags: arXiv_RO
author: Amr Alanwar, Fatima M. Anwar, Joao P Hespanha, Mani Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Time awareness is critical to a broad range of emerging applications -- in Cyber-Physical Systems and Internet of Things -- running on commodity platforms and operating systems. Traditionally, time is synchronized across devices through a best-effort background service whose performance is neither observable nor controllable, thus consuming system resources independently of application needs while not allowing the applications and OS services to adapt to changes in uncertainty in system time. We advocate for rethinking how time is managed in a system stack. In this paper, we propose a new clock model that characterizes various sources of timing uncertainties in true time. We then present a Kalman filter based time synchronization protocol that adapts to the uncertainties exposed by the clock model. Our realization of a uncertainty-aware clock model and synchronization protocol is based on a standard embedded Linux platform.

##### Abstract (translated by Google)
时间意识对于在商品平台和操作系统上运行的广泛的新兴应用（在Cyber​​-Physical Systems和物联网）至关重要。传统上，通过尽力而为的后台服务在各个设备间同步时间，但后台服务的性能既不可观察也不可控制，因此不依赖于应用程序需求而消耗系统资源，同时又不允许应用程序和OS服务适应系统时间不确定性的变化。我们主张重新思考如何在系统堆栈中管理时间。在这篇文章中，我们提出了一个新的时钟模型来描述时间不确定性的各种来源。然后，我们提出一个基于卡尔曼滤波器的时间同步协议，适应时钟模型暴露的不确定性。我们对不确定感知时钟模型和同步协议的实现基于标准的嵌入式Linux平台。

##### URL
[http://arxiv.org/abs/1802.00922](http://arxiv.org/abs/1802.00922)

##### PDF
[http://arxiv.org/pdf/1802.00922](http://arxiv.org/pdf/1802.00922)

