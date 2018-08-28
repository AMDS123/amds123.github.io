---
layout: post
title: "Scale Drift Correction of Camera Geo-Localization using Geo-Tagged Images"
date: 2018-08-26 12:43:34
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Kazuya Iwami, Satoshi Ikehata, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
Camera geo-localization from a monocular video is a fundamental task for video analysis and autonomous navigation. Although 3D reconstruction is a key technique to obtain camera poses, monocular 3D reconstruction in a large environment tends to result in the accumulation of errors in rotation, translation, and especially in scale: a problem known as scale drift. To overcome these errors, we propose a novel framework that integrates incremental structure from motion (SfM) and a scale drift correction method utilizing geo-tagged images, such as those provided by Google Street View. Our correction method begins by obtaining sparse 6-DoF correspondences between the reconstructed 3D map coordinate system and the world coordinate system, by using geo-tagged images. Then, it corrects scale drift by applying pose graph optimization over Sim(3) constraints and bundle adjustment. Experimental evaluations on large-scale datasets show that the proposed framework not only sufficiently corrects scale drift, but also achieves accurate geo-localization in a kilometer-scale environment.

##### Abstract (translated by Google)
单眼视频的相机地理定位是视频分析和自主导航的基本任务。尽管3D重建是获得相机姿势的关键技术，但是在大环境中的单眼3D重建倾向于导致旋转，平移，尤其是尺度上的误差累积：称为尺度漂移的问题。为了克服这些错误，我们提出了一种新的框架，它集成了来自运动的增量结构（SfM）和利用地理标记图像的比例漂移校正方法，例如Google街景提供的图像。我们的校正方法首先通过使用地理标记图像获得重建的3D地图坐标系与世界坐标系之间的稀疏6-DoF对应关系。然后，它通过在Sim（3）约束和束调整上应用姿势图优化来校正尺度漂移。对大规模数据集的实验评估表明，所提出的框架不仅可以充分地校正尺度漂移，而且可以在一公里规模的环境中实现精确的地理定位。

##### URL
[http://arxiv.org/abs/1808.08544](http://arxiv.org/abs/1808.08544)

##### PDF
[http://arxiv.org/pdf/1808.08544](http://arxiv.org/pdf/1808.08544)

