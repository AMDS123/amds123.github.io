---
layout: post
title: "Learning to Fly by Crashing"
date: 2017-04-27 00:13:19
categories: arXiv_CV
tags: arXiv_CV Drone
author: Dhiraj Gandhi, Lerrel Pinto, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
How do you learn to navigate an Unmanned Aerial Vehicle (UAV) and avoid obstacles? One approach is to use a small dataset collected by human experts: however, high capacity learning algorithms tend to overfit when trained with little data. An alternative is to use simulation. But the gap between simulation and real world remains large especially for perception problems. The reason most research avoids using large-scale real data is the fear of crashes! In this paper, we propose to bite the bullet and collect a dataset of crashes itself! We build a drone whose sole purpose is to crash into objects: it samples naive trajectories and crashes into random objects. We crash our drone 11,500 times to create one of the biggest UAV crash dataset. This dataset captures the different ways in which a UAV can crash. We use all this negative flying data in conjunction with positive data sampled from the same trajectories to learn a simple yet powerful policy for UAV navigation. We show that this simple self-supervised model is quite effective in navigating the UAV even in extremely cluttered environments with dynamic obstacles including humans. For supplementary video see: this https URL

##### Abstract (translated by Google)
你如何学习驾驶无人机（UAV）并避开障碍物？一种方法是使用由人类专家收集的小型数据集：然而，高容量学习算法在用少量数据训练时倾向于过度拟合。另一种方法是使用模拟。但是模拟与真实世界之间的差距仍然很大，特别是对于感知问题。大多数研究避免使用大规模实际数据的原因是对崩溃的恐惧！在本文中，我们建议咬紧牙关，收集崩溃数据集本身！我们制造了一个无人机，其唯一目的是撞击到物体上：它将幼稚的轨迹和碰撞抽样成随机的物体。我们使我们的无人机失事了11500次，创造了一架最大的无人机坠毁数据集。这个数据集捕捉了一个无人机可以崩溃的不同方式。我们将所有这些负面飞行数据与从相同轨迹采样的正面数据结合起来，为无人机导航学习一个简单而强大的策略。我们表明，这个简单的自我监督模型是相当有效的导航无人机甚至在包括人类在内的动态障碍在非常混乱的环境。有关补充视频，请参阅：https网址

##### URL
[https://arxiv.org/abs/1704.05588](https://arxiv.org/abs/1704.05588)

##### PDF
[https://arxiv.org/pdf/1704.05588](https://arxiv.org/pdf/1704.05588)

