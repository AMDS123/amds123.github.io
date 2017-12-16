---
layout: post
title: "RADNET: Radiologist Level Accuracy using Deep Learning for HEMORRHAGE detection in CT Scans"
date: 2017-10-13 14:14:39
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Prediction Detection
author: Monika Grewal, Muktabh Mayank Srivastava, Pulkit Kumar, Srikrishna Varadarajan
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a deep learning approach for automated brain hemorrhage detection from computed tomography (CT) scans. Our model emulates the procedure followed by radiologists to analyse a 3D CT scan in real-world. Similar to radiologists, the model sifts through 2D cross-sectional slices while paying close attention to potential hemorrhagic regions. Further, the model utilizes 3D context from neighboring slices to improve predictions at each slice and subsequently, aggregates the slice-level predictions to provide diagnosis at CT level. We refer to our proposed approach as Recurrent Attention DenseNet (RADnet) as it employs original DenseNet architecture along with adding the components of attention for slice level predictions and recurrent neural network layer for incorporating 3D context. The real-world performance of RADnet has been benchmarked against independent analysis performed by three senior radiologists for 77 brain CTs. RADnet demonstrates 81.82% hemorrhage prediction accuracy at CT level that is comparable to radiologists. Further, RADnet achieves higher recall than two of the three radiologists, which is remarkable.

##### Abstract (translated by Google)
我们描述了从计算机断层扫描（CT）扫描自动脑出血检测的深度学习方法。我们的模型模拟放射科医师在真实世界中分析3D CT扫描的过程。与放射科医师类似，该模型通过2D截面切片筛选，同时密切关注潜在的出血区域。此外，该模型利用来自相邻切片的3D上下文来改善每个切片处的预测，并且随后聚集切片层级预测以提供CT水平的诊断。我们将我们提出的方法称为经常性注意力DenseNet（RADnet），因为它采用了原始的DenseNet体系结构，同时增加了切片层级预测的关注组件和用于结合3D环境的递归神经网络层。 RADnet的真实性能已经被三位资深放射科医师对77例脑CT进行独立分析的基准。 RADnet在CT水平显示出81.82％的出血预测准确度，与放射科医师相当。此外，RADnet比三位放射科医师中的两位获得更高的召回率，这是显着的。

##### URL
[https://arxiv.org/abs/1710.04934](https://arxiv.org/abs/1710.04934)

##### PDF
[https://arxiv.org/pdf/1710.04934](https://arxiv.org/pdf/1710.04934)

