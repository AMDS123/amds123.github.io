---
layout: post
title: "L1 guidance logic extension for small UAVs: handling high winds and small loiter radii"
date: 2018-05-23 18:00:06
categories: arXiv_RO
tags: arXiv_RO
author: Thomas Stastny
mathjax: true
---

* content
{:toc}

##### Abstract
L1 guidance logic is one of the most widely used path following controllers for small fixed-wing unmanned aerial vehicles (UAVs), primarily due to its simplicity (low-cost implementation on embedded on-board processors, e.g. micro-controllers) and ability to track both circles and lines, which make up the vast majority of a typical fixed-wing vehicle's flight plan. The logic was later extended for speed independent dynamic similarity with an adaptive L1 distance, a formulation currently used on common open-source autopilot platforms. Two primary drawbacks remain, specific to small, slow flying fixed-wing UAVs; namely, 1) the combination of low operator defined gains and high ground speeds may violate the bounds of the algorithms convergence region for the case of loiter circles with small radii and 2) L1 logic breaks down when wind speeds exceed the vehicle's airspeed, another common predicament for small, slow-flying UAVs. This brief presents simple extensions to this extensively field tested algorithm, allowing legacy operators to keep existing controller tunings while taking advantage of the enhanced performance and safety features developed within.

##### Abstract (translated by Google)
L1引导逻辑是小型固定翼无人机（UAV）控制器应用最广泛的路径之一，主要原因在于其简单性（嵌入式板载处理器，例如微控制器的低成本实施）以及跟踪构成绝大多数典型固定翼飞行器飞行计划的圆圈和线条。该逻辑后来被扩展用于与自适应L1距离的速度独立动态相似性，该距离是目前在通用开源自动驾驶平台上使用的公式。针对小型，慢速飞行的固定翼无人机仍存在两个主要缺陷;即1）低运营商定义增益和高地面速度的组合可能会违反算法收敛区域的界限，对于半径较小的环形场景，以及2）当风速超过车辆空速时L1逻辑中断，另一个常见困难的小型慢行无人机。本简要介绍了这种广泛现场测试算法的简单扩展，允许传统操作员保留现有控制器调谐，同时利用其内部开发的增强型性能和安全功能。

##### URL
[http://arxiv.org/abs/1804.04209](http://arxiv.org/abs/1804.04209)

##### PDF
[http://arxiv.org/pdf/1804.04209](http://arxiv.org/pdf/1804.04209)

