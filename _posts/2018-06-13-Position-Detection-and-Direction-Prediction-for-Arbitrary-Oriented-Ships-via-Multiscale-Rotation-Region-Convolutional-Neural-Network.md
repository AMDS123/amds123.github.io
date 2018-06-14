---
layout: post
title: "Position Detection and Direction Prediction for Arbitrary-Oriented Ships via Multiscale Rotation Region Convolutional Neural Network"
date: 2018-06-13 02:48:44
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Xue Yang, Hao Sun, Xian Sun, Menglong Yan, Zhi Guo, Kun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Ship detection is of great importance and full of challenges in the field of remote sensing. The complexity of application scenarios, the redundancy of detection region, and the difficulty of dense ship detection are all the main obstacles that limit the successful operation of traditional methods in ship detection. In this paper, we propose a brand new detection model based on multiscale rotational region convolutional neural network to solve the problems above. This model is mainly consist of five consecutive parts: Dense Feature Pyramid Network (DFPN), adaptive region of interest (ROI) Align, rotational bounding box regression, prow direction prediction and rotational nonmaximum suppression (R-NMS). First of all, the low-level location information and high-level semantic information are fully utilized through multiscale feature networks. Then, we design adaptive ROI Align to obtain high quality proposals which remain complete spatial and semantic information. Unlike most previous approaches, the prediction obtained by our method is the minimum bounding rectangle of the object with less redundant regions. Therefore, rotational region detection framework is more suitable to detect the dense object than traditional detection model. Additionally, we can find the berthing and sailing direction of ship through prediction. A detailed evaluation based on SRSS and DOTA dataset for rotation detection shows that our detection method has a competitive performance.

##### Abstract (translated by Google)
船舶检测在遥感领域具有非常重要的意义和挑战性。应用场景的复杂性，检测区域的冗余度以及密集舰船检测的难度等都是限制传统舰船检测方法成功运行的主要障碍。在本文中，我们提出了一种基于多尺度旋转域卷积神经网络的全新检测模型来解决上述问题。该模型主要由五部分组成：稠密特征金字塔网络（DFPN），自适应感兴趣区域（ROI）对齐，旋转边界框回归，船首方向预测和旋转非最大抑制（R-NMS）。首先，通过多尺度特征网络充分利用低层位置信息和高层语义信息。然后，我们设计自适应ROI对齐来获得高质量的提案，这些提案保留了完整的空间和语义信息。与大多数先前的方法不同，我们的方法获得的预测是具有较少冗余区域的对象的最小边界矩形。因此，旋转区域检测框架比传统检测模型更适合检测密集对象。另外，我们可以通过预测找到船舶的靠泊和航行方向。基于SRSS和DOTA数据集进行旋转检测的详细评估表明，我们的检测方法具有竞争性表现。

##### URL
[http://arxiv.org/abs/1806.04828](http://arxiv.org/abs/1806.04828)

##### PDF
[http://arxiv.org/pdf/1806.04828](http://arxiv.org/pdf/1806.04828)

