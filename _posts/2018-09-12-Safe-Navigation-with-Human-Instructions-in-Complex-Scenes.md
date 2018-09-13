---
layout: post
title: "Safe Navigation with Human Instructions in Complex Scenes"
date: 2018-09-12 07:09:08
categories: arXiv_RO
tags: arXiv_RO Object_Detection Face Detection
author: Zhe Hu, Jia Pan, Tingxiang Fan, Ruigang Yang, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a robotic navigation algorithm with natural language interfaces, which enables a robot to safely walk through a changing environment with moving persons by following human instructions such as "go to the restaurant and keep away from people". We first classify human instructions into three types: the goal, the constraints, and uninformative phrases. Next, we provide grounding for the extracted goal and constraint items in a dynamic manner along with the navigation process, to deal with the target objects that are too far away for sensor observation and the appearance of moving obstacles like humans. In particular, for a goal phrase (e.g., "go to the restaurant"), we ground it to a location in a predefined semantic map and treat it as a goal for a global motion planner, which plans a collision-free path in the workspace for the robot to follow. For a constraint phrase (e.g., "keep away from people"), we dynamically add the corresponding constraint into a local planner by adjusting the values of a local costmap according to the results returned by the object detection module. The updated costmap is then used to compute a local collision avoidance control for the safe navigation of the robot. By combining natural language processing, motion planning, and computer vision, our developed system is demonstrated to be able to successfully follow natural language navigation instructions to achieve navigation tasks in both simulated and real-world scenarios. Videos are available at this https URL

##### Abstract (translated by Google)
在本文中，我们提出了一种具有自然语言界面的机器人导航算法，通过遵循人们的指示，例如“去餐厅，远离人”，机器人可以安全地穿越不断变化的环境。我们首先将人类指令分为三类：目标，约束和无信息短语。接下来，我们以动态的方式为导出的目标和约束项目提供基础以及导航过程，以处理对于传感器观察而言太远的目标对象以及像人类一样移动障碍物的外观。特别地，对于目标短语（例如，“去餐馆”），我们将其接地到预定义语义地图中的位置并将其视为全局运动规划器的目标，其计划在其中的无冲突路径。机器人要遵循的工作空间。对于约束短语（例如，“远离人”），我们通过根据对象检测模块返回的结果调整本地成本映射的值，将相应的约束动态地添加到本地规划器中。然后使用更新的成本图来计算机器人安全导航的局部碰撞避免控制。通过结合自然语言处理，运动规划和计算机视觉，我们开发的系统被证明能够成功地遵循自然语言导航指令，以在模拟和现实场景中实现导航任务。此https网址提供了视频

##### URL
[https://arxiv.org/abs/1809.04280](https://arxiv.org/abs/1809.04280)

##### PDF
[https://arxiv.org/pdf/1809.04280](https://arxiv.org/pdf/1809.04280)

