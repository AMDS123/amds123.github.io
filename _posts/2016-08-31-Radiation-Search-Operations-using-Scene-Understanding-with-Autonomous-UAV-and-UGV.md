---
layout: post
title: "Radiation Search Operations using Scene Understanding with Autonomous UAV and UGV"
date: 2016-08-31 20:00:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Inference Prediction Detection
author: Gordon Christie, Adam Shoemaker, Kevin Kochersberger, Pratap Tokekar, Lance McLean, Alexander Leonessa
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomously searching for hazardous radiation sources requires the ability of the aerial and ground systems to understand the scene they are scouting. In this paper, we present systems, algorithms, and experiments to perform radiation search using unmanned aerial vehicles (UAV) and unmanned ground vehicles (UGV) by employing semantic scene segmentation. The aerial data is used to identify radiological points of interest, generate an orthophoto along with a digital elevation model (DEM) of the scene, and perform semantic segmentation to assign a category (e.g. road, grass) to each pixel in the orthophoto. We perform semantic segmentation by training a model on a dataset of images we collected and annotated, using the model to perform inference on images of the test area unseen to the model, and then refining the results with the DEM to better reason about category predictions at each pixel. We then use all of these outputs to plan a path for a UGV carrying a LiDAR to map the environment and avoid obstacles not present during the flight, and a radiation detector to collect more precise radiation measurements from the ground. Results of the analysis for each scenario tested favorably. We also note that our approach is general and has the potential to work for a variety of different sensing tasks.

##### Abstract (translated by Google)
自主寻找危险的辐射源需要空中和地面系统了解他们正在侦察的场景。在本文中，我们提出了系统，算法和实验，使用无人机（UAV）和无人地面车辆（UGV）进行辐射搜索，采用语义场景分割。航空数据被用于识别放射性的兴趣点，与场景的数字高程模型（DEM）一起生成正射影像，并且执行语义分割以向正射影像中的每个像素分配类别（例如道路，草地）。我们进行语义分割，通过对我们收集和注释的图像数据集上的模型进行训练，使用模型对模型中看不见的测试区域图像进行推理，然后用DEM对结果进行细化，以更好地推断每个像素。然后，我们使用所有这些输出为携带LiDAR的UGV规划一条路径，以便映射环境并避开在飞行过程中不存在的障碍物，并使用辐射探测器从地面收集更精确的辐射测量值。对每种情况的分析结果都是有利的。我们也注意到，我们的方法是一般的，并有可能用于各种不同的感测任务。

##### URL
[https://arxiv.org/abs/1609.00017](https://arxiv.org/abs/1609.00017)

##### PDF
[https://arxiv.org/pdf/1609.00017](https://arxiv.org/pdf/1609.00017)

