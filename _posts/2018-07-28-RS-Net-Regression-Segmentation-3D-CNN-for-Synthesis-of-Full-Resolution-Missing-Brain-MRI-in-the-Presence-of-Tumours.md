---
layout: post
title: "RS-Net: Regression-Segmentation 3D CNN for Synthesis of Full Resolution Missing Brain MRI in the Presence of Tumours"
date: 2018-07-28 19:36:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference
author: Raghav Mehta, Tal Arbel
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate synthesis of a full 3D MR image containing tumours from available MRI (e.g. to replace an image that is currently unavailable or corrupted) would provide a clinician as well as downstream inference methods with important complementary information for disease analysis. In this paper, we present an end-to-end 3D convolution neural network that takes a set of acquired MR image sequences (e.g. T1, T2, T1ce) as input and concurrently performs (1) regression of the missing full resolution 3D MRI (e.g. FLAIR) and (2) segmentation of the tumour into subtypes (e.g. enhancement, core). The hypothesis is that this would focus the network to perform accurate synthesis in the area of the tumour. Experiments on the BraTS 2015 and 2017 datasets [1] show that: (1) the proposed method gives better performance than state-of-the-art methods in terms of established global evaluation metrics (e.g. PSNR), (2) replacing real MR volumes with the synthesized MRI does not lead to significant degradation in tumour and sub-structure segmentation accuracy. The system further provides uncertainty estimates based on Monte Carlo (MC) dropout [11] for the synthesized volume at each voxel, permitting quantification of the system's confidence in the output at each location.

##### Abstract (translated by Google)
准确合成包含来自可用MRI的肿瘤的全3D MR图像（例如，替换当前不可用或已损坏的图像）将为临床医生以及下游推断方法提供用于疾病分析的重要补充信息。在本文中，我们提出了一个端到端的3D卷积神经网络，它采用一组采集的MR图像序列（例如T1，T2，T1ce）作为输入，同时执行（1）丢失全分辨率3D MRI的回归（例如FLAIR）和（2）将肿瘤分割成亚型（例如增强，核心）。假设是这将使网络集中在肿瘤区域进行准确的合成。对BraTS 2015和2017数据集[1]的实验表明：（1）所提出的方法在已建立的全局评估指标（例如PSNR）方面比最先进的方法提供更好的性能，（2）替换真实的MR具有合成MRI的体积不会导致肿瘤和子结构分割准确性的显着降低。该系统进一步提供基于蒙特卡罗（MC）丢失[11]的不确定性估计，用于每个体素处的合成体积，允许量化系统对每个位置的输出的置信度。

##### URL
[http://arxiv.org/abs/1807.10972](http://arxiv.org/abs/1807.10972)

##### PDF
[http://arxiv.org/pdf/1807.10972](http://arxiv.org/pdf/1807.10972)

