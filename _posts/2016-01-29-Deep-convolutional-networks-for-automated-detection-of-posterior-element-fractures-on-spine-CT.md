---
layout: post
title: "Deep convolutional networks for automated detection of posterior-element fractures on spine CT"
date: 2016-01-29 21:48:13
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Detection
author: Holger R. Roth, Yinong Wang, Jianhua Yao, Le Lu, Joseph E. Burns, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Injuries of the spine, and its posterior elements in particular, are a common occurrence in trauma patients, with potentially devastating consequences. Computer-aided detection (CADe) could assist in the detection and classification of spine fractures. Furthermore, CAD could help assess the stability and chronicity of fractures, as well as facilitate research into optimization of treatment paradigms. In this work, we apply deep convolutional networks (ConvNets) for the automated detection of posterior element fractures of the spine. First, the vertebra bodies of the spine with its posterior elements are segmented in spine CT using multi-atlas label fusion. Then, edge maps of the posterior elements are computed. These edge maps serve as candidate regions for predicting a set of probabilities for fractures along the image edges using ConvNets in a 2.5D fashion (three orthogonal patches in axial, coronal and sagittal planes). We explore three different methods for training the ConvNet using 2.5D patches along the edge maps of 'positive', i.e. fractured posterior-elements and 'negative', i.e. non-fractured elements. An experienced radiologist retrospectively marked the location of 55 displaced posterior-element fractures in 18 trauma patients. We randomly split the data into training and testing cases. In testing, we achieve an area-under-the-curve of 0.857. This corresponds to 71% or 81% sensitivities at 5 or 10 false-positives per patient, respectively. Analysis of our set of trauma patients demonstrates the feasibility of detecting posterior-element fractures in spine CT images using computer vision techniques such as deep convolutional networks.

##### Abstract (translated by Google)
创伤患者常常发生脊柱损伤，尤其是后部损伤，可能造成严重后果。计算机辅助检测（CADe）可以帮助检测和分类脊柱骨折。此外，计算机辅助设计可以帮助评估骨折的稳定性和慢性，并促进对治疗范式优化的研究。在这项工作中，我们应用深度卷积网络（ConvNets）来自动检测脊柱后部骨折。首先，使用多图谱标签融合在脊柱CT中分割脊椎的脊椎体及其后部元素。然后，计算后验元素的边缘图。这些边缘图用作候选区域，以2.5D方式使用ConvNets（轴向，冠状面和矢状面中的三个正交斑块）来预测沿图像边缘的一组骨折的概率。我们探索了三种不同的方法来训练ConvNet，使用沿着“正”的边缘图的2.5D块，即断裂后的元素和“负”，即非断裂的元素。一位经验丰富的放射科医师回顾性地分析了18例创伤患者55个移位后路骨折的位置。我们将数据随机分为训练和测试案例。在测试中，我们实现了0.857的曲线下面积。这相当于分别在每个患者5或10个假阳性时的71％或81％的敏感性。我们对创伤患者的分析表明使用深度卷积网络等计算机视觉技术检测脊柱CT图像中后部骨折的可行性。

##### URL
[https://arxiv.org/abs/1602.00020](https://arxiv.org/abs/1602.00020)

##### PDF
[https://arxiv.org/pdf/1602.00020](https://arxiv.org/pdf/1602.00020)

