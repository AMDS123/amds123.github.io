---
layout: post
title: "Scene Coordinate and Correspondence Learning for Imabe-Based Localization"
date: 2018-05-22 08:12:03
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Mai Bui, Shadi Albarqouni, Slobodan Ilic, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Scene coordinate regression has become an essential part of current camera re-localization methods. Different versions in the form of regression forests and deep learning methods have been successfully applied to estimate the corresponding camera pose given a single input image. In this work, we propose to regress scene coordinates pixel-wise for a given RGB image using deep learning. Compared to the recent methods, which usually employ RANSAC to obtain a robust pose estimate from the established point correspondences, we propose to regress confidences of these correspondences, which allows us to immediately discard erroneous predictions resulting in boosting initial pose estimates. Finally, the resulting confidences can be used to score initial pose hypothesis and aid in pose refinement, offering a generalized solution to solve this task.

##### Abstract (translated by Google)
场景坐标回归已经成为当前相机重新定位方法的重要部分。以回归森林和深度学习方法为形式的不同版本已成功应用于估算给定单个输入图像的相应姿态。在这项工作中，我们建议使用深度学习对给定的RGB图像以像素为单位对场景坐标进行回归。与通常使用RANSAC从已建立的点对应关系获得稳健姿态估计的最近方法相比，我们建议对这些对应关系的置信度进行回归，这使我们能够立即丢弃错误的预测结果，从而提高初始姿态估计值。最后，由此产生的置信度可以用来评估初始姿势假设并帮助姿态细化，为解决这一任务提供了一个通用的解决方案。

##### URL
[https://arxiv.org/abs/1805.08443](https://arxiv.org/abs/1805.08443)

##### PDF
[https://arxiv.org/pdf/1805.08443](https://arxiv.org/pdf/1805.08443)

