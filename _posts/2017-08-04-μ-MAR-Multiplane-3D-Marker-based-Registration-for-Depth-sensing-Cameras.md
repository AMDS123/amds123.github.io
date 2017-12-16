---
layout: post
title: "μ-MAR: Multiplane 3D Marker based Registration for Depth-sensing Cameras"
date: 2017-08-04 07:35:22
categories: arXiv_CV
tags: arXiv_CV Inference Quantitative
author: Marcelo Saval-Calvo, Jorge Azorin-Lopez, Andres Fuster-Guillo, Higinio Mora-Mora
mathjax: true
---

* content
{:toc}

##### Abstract
Many applications including object reconstruction, robot guidance, and scene mapping require the registration of multiple views from a scene to generate a complete geometric and appearance model of it. In real situations, transformations between views are unknown an it is necessary to apply expert inference to estimate them. In the last few years, the emergence of low-cost depth-sensing cameras has strengthened the research on this topic, motivating a plethora of new applications. Although they have enough resolution and accuracy for many applications, some situations may not be solved with general state-of-the-art registration methods due to the Signal-to-Noise ratio (SNR) and the resolution of the data provided. The problem of working with low SNR data, in general terms, may appear in any 3D system, then it is necessary to propose novel solutions in this aspect. In this paper, we propose a method, {\mu}-MAR, able to both coarse and fine register sets of 3D points provided by low-cost depth-sensing cameras, despite it is not restricted to these sensors, into a common coordinate system. The method is able to overcome the noisy data problem by means of using a model-based solution of multiplane registration. Specifically, it iteratively registers 3D markers composed by multiple planes extracted from points of multiple views of the scene. As the markers and the object of interest are static in the scenario, the transformations obtained for the markers are applied to the object in order to reconstruct it. Experiments have been performed using synthetic and real data. The synthetic data allows a qualitative and quantitative evaluation by means of visual inspection and Hausdorff distance respectively. The real data experiments show the performance of the proposal using data acquired by a Primesense Carmine RGB-D sensor. The method has been compared to several state-of-the-art methods. The ...

##### Abstract (translated by Google)
包括对象重建，机器人引导和场景映射在内的许多应用都需要从场景中注册多个视图来生成一个完整的几何和外观模型。在实际情况下，视图之间的转换是未知的，因此有必要应用专家推断来估计它们。在过去的几年里，低成本深度传感相机的出现加强了对这个话题的研究，激发了大量的新应用。虽然它们在许多应用中具有足够的分辨率和精度，但是由于信噪比（SNR）和所提供的数据的分辨率，一些情况可能无法用一般的现有技术的注册方法来解决。总体而言，低信噪比数据处理的问题可能出现在任何3D系统中，因此有必要在这方面提出新的解决方案。在本文中，我们提出了一种{\ mu} -MAR方法，能够将由低成本深度相机提供的粗略和精细的三维点集（尽管不限于这些传感器）系统。该方法能够通过使用基于模型的多平面配准解决方案来克服噪声数据问题。具体来说，它迭代地记录由从场景的多个视点的点提取的多个平面组成的3D标记。由于场景中的标记和感兴趣的对象是静态的，因此将标记获得的变换应用于对象以便重建它。已经使用合成和真实数据进行了实验。综合数据可以通过视觉检查和豪斯多​​夫距离分别进行定性和定量评估。真实的数据实验使用Primesense Carmine RGB-D传感器获取的数据显示提议的性能。该方法已与几种最先进的方法进行了比较。那...

##### URL
[https://arxiv.org/abs/1708.01405](https://arxiv.org/abs/1708.01405)

##### PDF
[https://arxiv.org/pdf/1708.01405](https://arxiv.org/pdf/1708.01405)

