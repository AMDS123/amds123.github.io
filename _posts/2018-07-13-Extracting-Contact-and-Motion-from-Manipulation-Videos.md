---
layout: post
title: "Extracting Contact and Motion from Manipulation Videos"
date: 2018-07-13 00:15:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Detection
author: Konstantinos Zampogiannis, Kanishka Ganguly, Cornelia Fermuller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
When we physically interact with our environment using our hands, we touch objects and force them to move: contact and motion are defining properties of manipulation. In this paper, we present an active, bottom-up method for the detection of actor-object contacts and the extraction of moved objects and their motions in RGBD videos of manipulation actions. At the core of our approach lies non-rigid registration: we continuously warp a point cloud model of the observed scene to the current video frame, generating a set of dense 3D point trajectories. Under loose assumptions, we employ simple point cloud segmentation techniques to extract the actor and subsequently detect actor-environment contacts based on the estimated trajectories. For each such interaction, using the detected contact as an attention mechanism, we obtain an initial motion segment for the manipulated object by clustering trajectories in the contact area vicinity and then we jointly refine the object segment and estimate its 6DOF pose in all observed frames. Because of its generality and the fundamental, yet highly informative, nature of its outputs, our approach is applicable to a wide range of perception and planning tasks. We qualitatively evaluate our method on a number of input sequences and present a comprehensive robot imitation learning example, in which we demonstrate the crucial role of our outputs in developing action representations/plans from observation.

##### Abstract (translated by Google)
当我们用手与环境进行物理交互时，我们触摸物体并迫使它们移动：接触和运动定义了操纵的属性。在本文中，我们提出了一种主动的，自下而上的方法，用于检测演员 - 对象接触以及移动对象的提取及其在操纵动作的RGBD视频中的运动。我们的方法的核心是非刚性配准：我们不断地将观察到的场景的点云模型扭曲到当前视频帧，生成一组密集的3D点轨迹。在松散的假设下，我们采用简单的点云分割技术来提取行动者，并随后根据估计的轨迹检测行动者 - 环境接触。对于每个这样的交互，使用检测到的接触作为关注机制，我们通过聚类接触区域附近的轨迹来获得被操纵对象的初始运动段，然后我们共同细化对象段并估计其在所有观察帧中的6DOF姿势。由于其一般性和产出的基本但信息量大，我们的方法适用于广泛的感知和规划任务。我们定性地评估了我们在许多输入序列上的方法，并提供了一个全面的机器人模仿学习示例，其中我们展示了我们的输出在从观察开发行动表示/计划中的关键作用。

##### URL
[http://arxiv.org/abs/1807.04870](http://arxiv.org/abs/1807.04870)

##### PDF
[http://arxiv.org/pdf/1807.04870](http://arxiv.org/pdf/1807.04870)

