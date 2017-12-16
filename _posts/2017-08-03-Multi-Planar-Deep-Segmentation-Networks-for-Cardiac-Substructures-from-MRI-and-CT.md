---
layout: post
title: "Multi-Planar Deep Segmentation Networks for Cardiac Substructures from MRI and CT"
date: 2017-08-03 03:30:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative Detection
author: Aliasghar Mortazi, Jeremy Burt, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Non-invasive detection of cardiovascular disorders from radiology scans requires quantitative image analysis of the heart and its substructures. There are well-established measurements that radiologists use for diseases assessment such as ejection fraction, volume of four chambers, and myocardium mass. These measurements are derived as outcomes of precise segmentation of the heart and its substructures. The aim of this paper is to provide such measurements through an accurate image segmentation algorithm that automatically delineates seven substructures of the heart from MRI and/or CT scans. Our proposed method is based on multi-planar deep convolutional neural networks (CNN) with an adaptive fusion strategy where we automatically utilize complementary information from different planes of the 3D scans for improved delineations. For CT and MRI, we have separately designed three CNNs (the same architectural configuration) for three planes, and have trained the networks from scratch for voxel-wise labeling for the following cardiac structures: myocardium of left ventricle (Myo), left atrium (LA), left ventricle (LV), right atrium (RA), right ventricle (RV), ascending aorta (Ao), and main pulmonary artery (PA). We have evaluated the proposed method with 4-fold-cross validation on the multi-modality whole heart segmentation challenge (MM-WHS 2017) dataset. The precision and dice index of 0.93 and 0.90, and 0.87 and 0.85 were achieved for CT and MR images, respectively. While a CT volume was segmented about 50 seconds, an MRI scan was segmented around 17 seconds with the GPUs/CUDA implementation.

##### Abstract (translated by Google)
从放射学扫描非侵入性检测心血管疾病需要对心脏及其子结构进行定量的图像分析。有放射科医师用于评估射血分数，四室容积和心肌质量等疾病的完善测量方法。这些测量结果是精确分割心脏及其子结构的结果。本文的目的是通过精确的图像分割算法提供这样的测量，该算法从MRI和/或CT扫描中自动描绘心脏的七个子结构。我们提出的方法是基于具有自适应融合策略的多平面深度卷积神经网络（CNN），其中我们自动利用来自3D扫描的不同平面的补充信息来改善描绘。对于CT和MRI，我们已经为三个平面单独设计了三个CNN（相同的架构配置），并且从头开始训练网络以用于以下心脏结构的体素标记：左心室（Myo）的心肌，左心房（ LA），左心室（LV），右心房（RA），右心室（RV），升主动脉（Ao）和主肺动脉（PA）。我们已经在多模式整体心脏分割挑战（MM-WHS2017）数据集上对所提出的方法进行了4倍交叉验证。 CT和MR图像的精确度和骰子指数分别为0.93和0.90，分别为0.87和0.85。当CT体积被分割大约50秒时，利用GPU / CUDA实施在17秒左右将MRI扫描分割。

##### URL
[https://arxiv.org/abs/1708.00983](https://arxiv.org/abs/1708.00983)

##### PDF
[https://arxiv.org/pdf/1708.00983](https://arxiv.org/pdf/1708.00983)

