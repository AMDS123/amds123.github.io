---
layout: post
title: "Fast and Robust Detection of Fallen People from a Mobile Robot"
date: 2017-03-09 17:15:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Detection Relation
author: Morris Antonello, Marco Carraro, Marco Pierobon, Emanuele Menegatti
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with the problem of detecting fallen people lying on the floor by means of a mobile robot equipped with a 3D depth sensor. In the proposed algorithm, inspired by semantic segmentation techniques, the 3D scene is over-segmented into small patches. Fallen people are then detected by means of two SVM classifiers: the first one labels each patch, while the second one captures the spatial relations between them. This novel approach showed to be robust and fast. Indeed, thanks to the use of small patches, fallen people in real cluttered scenes with objects side by side are correctly detected. Moreover, the algorithm can be executed on a mobile robot fitted with a standard laptop making it possible to exploit the 2D environmental map built by the robot and the multiple points of view obtained during the robot navigation. Additionally, this algorithm is robust to illumination changes since it does not rely on RGB data but on depth data. All the methods have been thoroughly validated on the IASLAB-RGBD Fallen Person Dataset, which is published online as a further contribution. It consists of several static and dynamic sequences with 15 different people and 2 different environments.

##### Abstract (translated by Google)
本文论述了通过配备有3D深度传感器的移动机器人来检测躺在地板上的堕落人员的问题。在所提出的算法中，受到语义分割技术的启发，三维场景被过度分割成小块。然后通过两个SVM分类器检测下落的人：第一个标记每个补丁，而第二个则捕获它们之间的空间关系。这种新颖的方法显示出强劲和快速。事实上，由于使用了小块，所以正确地检测到真正的杂乱无章的场景与并排的物体。此外，该算法可以在配备有标准笔记本电脑的移动机器人上执行，使得可以利用由机器人构建的2D环境地图以及在机器人导航期间获得的多个视点。另外，由于这种算法不依赖于RGB数据，而是依赖于深度数据，所以该算法对照度变化是鲁棒的。所有的方法都已经在IASLAB-RGBD堕落人物数据集中得到了彻底的验证，该数据集在网上公布，作为进一步的贡献。它由几个静态和动态序列组成，有15个不同的人和2个不同的环境。

##### URL
[https://arxiv.org/abs/1703.03349](https://arxiv.org/abs/1703.03349)

##### PDF
[https://arxiv.org/pdf/1703.03349](https://arxiv.org/pdf/1703.03349)

