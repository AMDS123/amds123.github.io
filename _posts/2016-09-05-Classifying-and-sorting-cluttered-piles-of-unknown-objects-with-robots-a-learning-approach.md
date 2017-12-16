---
layout: post
title: "Classifying and sorting cluttered piles of unknown objects with robots: a learning approach"
date: 2016-09-05 07:44:40
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Janne V. Kujala, Tuomas J. Lukka, Harri Holopainen
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of sorting a densely cluttered pile of unknown objects using a robot. This yet unsolved problem is relevant in the robotic waste sorting business. By extending previous active learning approaches to grasping, we show a system that learns the task autonomously. Instead of predicting just whether a grasp succeeds, we predict the classes of the objects that end up being picked and thrown onto the target conveyor. Segmenting and identifying objects from the uncluttered target conveyor, as opposed to the working area, is easier due to the added structure since the thrown objects will be the only ones present. Instead of trying to segment or otherwise understand the cluttered working area in any way, we simply allow the controller to learn a mapping from an RGBD image in the neighborhood of the grasp to a predicted result---all segmentation etc. in the working area is implicit in the learned function. The grasp selection operates in two stages: The first stage is hardcoded and outputs a distribution of possible grasps that sometimes succeed. The second stage uses a purely learned criterion to choose the grasp to make from the proposal distribution created by the first stage. In an experiment, the system quickly learned to make good pickups and predict correctly, in advance, which class of object it was going to pick up and was able to sort the objects from a densely cluttered pile by color.

##### Abstract (translated by Google)
我们考虑使用机器人对一堆密集的未知物体进行分类的问题。这个尚未解决的问题与机器人垃圾分类业务相关。通过扩展先前的主动学习方法来抓住，我们展示了一个自主学习任务的系统。我们不是预测抓取是否成功，而是预测最终拾取并投掷到目标传送带上的物体的类别。从整齐的目标输送机，而不是工作区域分割和识别物体，由于添加的结构而更容易，因为抛出的物体将是唯一存在的物体。我们不是试图以任何方式分割或以其他方式理解混乱的工作区域，而是让控制器学习从抓握附近的RGBD图像到预测结果的映射 - 工作区域中的所有分割等隐含在学习函数中。把握的选择分两个阶段进行：第一阶段是硬编码的，并输出可能的抓取分配，有时会成功。第二阶段采用纯粹学习的标准，从第一阶段创建的提案分布中选择把握。在一个实验中，系统很快就学会了制作好拾音器，并且事先准确地预测要拾取哪一类物体，并且能够通过颜色将物体从繁琐的堆叠中分类出来。

##### URL
[https://arxiv.org/abs/1609.01044](https://arxiv.org/abs/1609.01044)

##### PDF
[https://arxiv.org/pdf/1609.01044](https://arxiv.org/pdf/1609.01044)

