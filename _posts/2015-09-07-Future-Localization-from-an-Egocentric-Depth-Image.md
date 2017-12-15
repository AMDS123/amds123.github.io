---
layout: post
title: "Future Localization from an Egocentric Depth Image"
date: 2015-09-07 15:51:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Quantitative Detection Relation Recognition
author: Hyun Soo Park, Yedong Niu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for future localization: to predict a set of plausible trajectories of ego-motion given a depth image. We predict paths avoiding obstacles, between objects, even paths turning around a corner into space behind objects. As a byproduct of the predicted trajectories of ego-motion, we discover in the image the empty space occluded by foreground objects. We use no image based features such as semantic labeling/segmentation or object detection/recognition for this algorithm. Inspired by proxemics, we represent the space around a person using an EgoSpace map, akin to an illustrated tourist map, that measures a likelihood of occlusion at the egocentric coordinate system. A future trajectory of ego-motion is modeled by a linear combination of compact trajectory bases allowing us to constrain the predicted trajectory. We learn the relationship between the EgoSpace map and trajectory from the EgoMotion dataset providing in-situ measurements of the future trajectory. A cost function that takes into account partial occlusion due to foreground objects is minimized to predict a trajectory. This cost function generates a trajectory that passes through the occluded space, which allows us to discover the empty space behind the foreground objects. We quantitatively evaluate our method to show predictive validity and apply to various real world scenes including walking, shopping, and social interactions.

##### Abstract (translated by Google)
本文提出了一种未来定位的方法：预测一组给定深度图像的自我运动轨迹。我们预测避开障碍物，物体之间的路径，甚至路径绕着物体转向空间的路径。作为自我运动的预测轨迹的副产品，我们在图像中发现被前景物体遮挡的空白空间。对于这种算法，我们不使用基于图像的特征，如语义标记/分割或对象检测/识别。受proxemics的启发，我们使用EgoSpace地图代表人物周围的空间，类似于一个插图的旅游地图，用于衡量在以自我为中心的坐标系下遮挡的可能性。自我运动的未来轨迹通过紧凑轨迹基线的线性组合模拟，使我们能够限制预测的轨迹。我们从EgoMotion数据集中了解EgoSpace地图和轨迹之间的关系，提供对未来轨迹的现场测量。考虑到由前景物体引起的部分遮挡的成本函数被最小化以预测轨迹。这个成本函数产生一个通过被遮挡的空间的轨迹，这使我们能够发现前景对象后面的空白空间。我们定量评估我们的方法，以显示预测的有效性，并适用于各种现实世界的场景，包括步行，购物和社交互动。

##### URL
[https://arxiv.org/abs/1509.02094](https://arxiv.org/abs/1509.02094)

##### PDF
[https://arxiv.org/pdf/1509.02094](https://arxiv.org/pdf/1509.02094)

