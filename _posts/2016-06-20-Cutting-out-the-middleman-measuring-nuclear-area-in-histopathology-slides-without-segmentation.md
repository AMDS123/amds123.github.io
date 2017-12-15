---
layout: post
title: "Cutting out the middleman: measuring nuclear area in histopathology slides without segmentation"
date: 2016-06-20 14:10:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Mitko Veta, Paul J. van Diest, Josien P.W. Pluim
mathjax: true
---

* content
{:toc}

##### Abstract
The size of nuclei in histological preparations from excised breast tumors is predictive of patient outcome (large nuclei indicate poor outcome). Pathologists take into account nuclear size when performing breast cancer grading. In addition, the mean nuclear area (MNA) has been shown to have independent prognostic value. The straightforward approach to measuring nuclear size is by performing nuclei segmentation. We hypothesize that given an image of a tumor region with known nuclei locations, the area of the individual nuclei and region statistics such as the MNA can be reliably computed directly from the image data by employing a machine learning model, without the intermediate step of nuclei segmentation. Towards this goal, we train a deep convolutional neural network model that is applied locally at each nucleus location, and can reliably measure the area of the individual nuclei and the MNA. Furthermore, we show how such an approach can be extended to perform combined nuclei detection and measurement, which is reminiscent of granulometry.

##### Abstract (translated by Google)
切除的乳腺肿瘤的组织学制剂中的核的大小预示患者结果（大的核表示不良的结果）。进行乳腺癌分级时，病理学家考虑到核的大小。另外，平均核面积（MNA）已被证明具有独立的预后价值。测量核大小的直接方法是通过执行核分割。我们假设给定一个肿瘤区域的已知核位置的图像，单个核和区域统计数据（例如MNA）的面积可以通过使用机器学习模型直接从图像数据可靠地计算，而不需要核的中间步骤分割。为了实现这个目标，我们训练了一个深度卷积神经网络模型，它被应用在每个核心位置的局部区域，并且可以可靠地测量单个核和MNA的面积。此外，我们展示了如何扩展这种方法来执行联合的核探测和测量，这是让人联想到粒度测量。

##### URL
[https://arxiv.org/abs/1606.06127](https://arxiv.org/abs/1606.06127)

##### PDF
[https://arxiv.org/pdf/1606.06127](https://arxiv.org/pdf/1606.06127)

