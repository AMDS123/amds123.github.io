---
layout: post
title: "Data Acquisition System with Shared Memory Network"
date: 2001-12-03 08:37:13
categories: arXiv_CV
tags: arXiv_CV
author: T. Masuda, T. Fukui, R. Tanaka, A. Yamashita
mathjax: true
---

* content
{:toc}

##### Abstract
The SPring-8 control system provides data acquisition software called Poller/Collector for periodic data taking. Its polling scheme does not support taking data synchronized with an event, and simultaneity in the data from the different VME systems is not guaranteed. Recently, requirement for fast and event-driven data acquisition has increased, and the synchronization of a set of data from the different VME systems is requested. We added new data-taking software to the standard framework with a shared memory network. We designed the software on the VME by updating the original framework that was already used for feedback control. The data filling process on a PC stores sets of the synchronized data on a shared memory board to the database. The shared memory boards provide 250Mbit/s transmission rate and are linked with optical fiber cables. We will install the system to the linac beam position monitors data acquisition as the first application.

##### Abstract (translated by Google)
SPring-8控制系统提供数据采集软件，称为轮询/采集器，用于定期采集数据。它的轮询方案不支持与事件同步的数据，并不保证来自不同VME系统的数据的同时性。最近，对快速和事件驱动的数据采集的需求增加，并且请求来自不同VME系统的一组数据的同步。我们增加了新的数据采集软件到共享内存网络的标准框架。我们通过更新已经用于反馈控制的原始框架来设计VME上的软件。 PC上的数据填充过程将共享存储器板上的同步数据组存储到数据库。共享内存板提供250Mbit / s的传输速率，并与光缆连接。我们将把系统安装到直线加速器位置监视器数据采集器作为第一个应用程序。

##### URL
[https://arxiv.org/abs/physics/0111130](https://arxiv.org/abs/physics/0111130)

##### PDF
[https://arxiv.org/pdf/physics/0111130](https://arxiv.org/pdf/physics/0111130)

