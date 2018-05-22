---
layout: post
title: "Object Localization and Motion Transfer learning with Capsules"
date: 2018-05-20 05:07:27
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning RNN Prediction Recognition
author: Weitang Liu, Emad Barsoum, John D. Owens
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by CapsNet's routing-by-agreement mechanism, with its ability to learn object properties, and by center-of-mass calculations from physics, we propose a CapsNet architecture with object coordinate atoms and an LSTM network for evaluation. The first is based on CapsNet but uses a new routing algorithm to find the objects' approximate positions in the image coordinate system, and the second is a parameterized affine transformation network that can predict future positions from past positions by learning the translation transformation from 2D object coordinates generated from the first network. We demonstrate the learned translation transformation is transferable to another dataset without the need to train the transformation network again. Only the CapsNet needs training on the new dataset. As a result, our work shows that object recognition and motion prediction can be separated, and that motion prediction can be transferred to another dataset with different object types.

##### Abstract (translated by Google)
受CapsNet协议路由协议机制的启发，凭借其学习对象属性的能力以及物理中心质量计算的能力，我们提出了一个带有对象坐标原子的CapsNet架构和一个用于评估的LSTM网络。第一种基于CapsNet，但使用新的路由算法来查找图像坐标系中对象的近似位置，第二种是参数化仿射变换网络，可通过学习2D对象的平移变换来预测过去位置的未来位置从第一网络生成的坐标。我们证明了学习到的转换转换可转移到另一个数据集，而不需要再次训练转换网络。只有CapsNet需要对新数据集进行培训。因此，我们的工作表明，可以将物体识别和运动预测分开，并且可以将运动预测转移到具有不同物体类型的另一个数据集。

##### URL
[https://arxiv.org/abs/1805.07706](https://arxiv.org/abs/1805.07706)

##### PDF
[https://arxiv.org/pdf/1805.07706](https://arxiv.org/pdf/1805.07706)

