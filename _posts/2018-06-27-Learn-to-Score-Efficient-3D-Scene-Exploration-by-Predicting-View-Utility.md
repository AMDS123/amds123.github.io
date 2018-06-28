---
layout: post
title: "Learn-to-Score: Efficient 3D Scene Exploration by Predicting View Utility"
date: 2018-06-27 09:09:50
categories: arXiv_CV
tags: arXiv_CV Drone CNN
author: Benjamin Hepp, Debadeepta Dey, Sudipta N. Sinha, Ashish Kapoor, Neel Joshi, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
Camera equipped drones are nowadays being used to explore large scenes and reconstruct detailed 3D maps. When free space in the scene is approximately known, an offline planner can generate optimal plans to efficiently explore the scene. However, for exploring unknown scenes, the planner must predict and maximize usefulness of where to go on the fly. Traditionally, this has been achieved using handcrafted utility functions. We propose to learn a better utility function that predicts the usefulness of future viewpoints. Our learned utility function is based on a 3D convolutional neural network. This network takes as input a novel volumetric scene representation that implicitly captures previously visited viewpoints and generalizes to new scenes. We evaluate our method on several large 3D models of urban scenes using simulated depth cameras. We show that our method outperforms existing utility measures in terms of reconstruction performance and is robust to sensor noise.

##### Abstract (translated by Google)
现在正在使用配备相机的无人机来探索大型场景并重建详细的3D地图。当场景中的空闲空间大致已知时，离线计划员可以生成最佳计划以高效地探索场景。然而，为了探索未知的场景，规划者必须预测并最大限度地发挥实际应用的实用性。传统上，这是使用手工实用功能实现的。我们建议学习一个能够预测未来观点有用性的更好的效用函数。我们学到的效用函数基于三维卷积神经网络。该网络将输入的新体积场景表示隐式捕获先前访问过的视点并推广到新场景。我们使用模拟深度相机在几个城市场景的大型3D模型上评估我们的方法。我们表明，我们的方法在重建性能方面优于现有的实用性措施，并且对传感器噪声强劲。

##### URL
[http://arxiv.org/abs/1806.10354](http://arxiv.org/abs/1806.10354)

##### PDF
[http://arxiv.org/pdf/1806.10354](http://arxiv.org/pdf/1806.10354)

