---
layout: post
title: "3D Face Hallucination from a Single Depth Frame"
date: 2018-09-13 04:13:56
categories: arXiv_CV
tags: arXiv_CV Face
author: Shu Liang, Ira Kemelmacher-Shlizerman, Linda G. Shapiro
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm that takes a single frame of a person's face from a depth camera, e.g., Kinect, and produces a high-resolution 3D mesh of the input face. We leverage a dataset of 3D face meshes of 1204 distinct individuals ranging from age 3 to 40, captured in a neutral expression. We divide the input depth frame into semantically significant regions (eyes, nose, mouth, cheeks) and search the database for the best matching shape per region. We further combine the input depth frame with the matched database shapes into a single mesh that results in a high-resolution shape of the input person. Our system is fully automatic and uses only depth data for matching, making it invariant to imaging conditions. We evaluate our results using ground truth shapes, as well as compare to state-of-the-art shape estimation methods. We demonstrate the robustness of our local matching approach with high-quality reconstruction of faces that fall outside of the dataset span, e.g., faces older than 40 years old, facial expressions, and different ethnicities.

##### Abstract (translated by Google)
我们提出了一种算法，该算法从深度相机（例如Kinect）获取人脸的单帧，并产生输入面的高分辨率3D网格。我们利用中性表达式捕获的1204个不同个体的3D面部网格数据集，范围从3到40岁。我们将输入深度帧划分为语义上重要的区域（眼睛，鼻子，嘴巴，脸颊），并在数据库中搜索每个区域的最佳匹配形状。我们进一步将输入深度框架与匹配的数据库形状组合成单个网格，从而产生输入人员的高分辨率形状。我们的系统是全自动的，仅使用深度数据进行匹配，使其对成像条件不变。我们使用地面实况形状评估我们的结果，并与最先进的形状估计方法进行比较。我们展示了我们的局部匹配方法的稳健性，以及超出数据集范围的面部的高质量重建，例如，年龄超过40岁的面部，面部表情和不同的种族。

##### URL
[http://arxiv.org/abs/1809.04764](http://arxiv.org/abs/1809.04764)

##### PDF
[http://arxiv.org/pdf/1809.04764](http://arxiv.org/pdf/1809.04764)

