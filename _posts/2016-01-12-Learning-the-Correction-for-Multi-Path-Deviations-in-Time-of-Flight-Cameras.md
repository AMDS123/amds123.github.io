---
layout: post
title: "Learning the Correction for Multi-Path Deviations in Time-of-Flight Cameras"
date: 2016-01-12 11:17:58
categories: arXiv_CV
tags: arXiv_CV
author: Mojmir Mutny, Rahul Nair, Jens-Malte Gottfried
mathjax: true
---

* content
{:toc}

##### Abstract
The Multipath effect in Time-of-Flight(ToF) cameras still remains to be a challenging problem that hinders further processing of 3D data information. Based on the evidence from previous literature, we explored the possibility of using machine learning techniques to correct this effect. Firstly, we created two new datasets of of ToF images rendered via ToF simulator of LuxRender. These two datasets contain corners in multiple orientations and with different material properties. We chose scenes with corners as multipath effects are most pronounced in corners. Secondly, we used this dataset to construct a learning model to predict real valued corrections to the ToF data using Random Forests. We found out that in our smaller dataset we were able to predict real valued correction and improve the quality of depth images significantly by removing multipath bias. With our algorithm, we improved relative per-pixel error from average value of 19% to 3%. Additionally, variance of the error was lowered by an order of magnitude.

##### Abstract (translated by Google)
飞行时间（ToF）相机中的多径效应仍然是阻碍3D数据信息的进一步处理的具有挑战性的问题。基于以前文献的证据，我们探讨了使用机器学习技术来纠正这种效应的可能性。首先，我们通过LuxRender的ToF模拟器创建了两个ToF图像的新数据集。这两个数据集包含多个方向的角落和不同的材料属性。我们选择了角落场景，因为多角度效应在角落中最为明显。其次，我们使用这个数据集来构建一个学习模型来预测使用随机森林对ToF数据进行实值修正。我们发现，在我们较小的数据集中，我们能够通过消除多路径偏差来预测实值校正并显着提高深度图像的质量。使用我们的算法，我们将相对每像素误差从19％的平均值提高到3％。另外，误差的方差降低了一个数量级。

##### URL
[https://arxiv.org/abs/1512.04077](https://arxiv.org/abs/1512.04077)

##### PDF
[https://arxiv.org/pdf/1512.04077](https://arxiv.org/pdf/1512.04077)

