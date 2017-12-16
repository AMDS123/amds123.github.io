---
layout: post
title: "Funnel-Structured Cascade for Multi-View Face Detection with Alignment-Awareness"
date: 2016-09-23 10:43:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Face Prediction Detection Face_Detection
author: Shuzhe Wu, Meina Kan, Zhenliang He, Shiguang Shan, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view face detection in open environment is a challenging task due to diverse variations of face appearances and shapes. Most multi-view face detectors depend on multiple models and organize them in parallel, pyramid or tree structure, which compromise between the accuracy and time-cost. Aiming at a more favorable multi-view face detector, we propose a novel funnel-structured cascade (FuSt) detection framework. In a coarse-to-fine flavor, our FuSt consists of, from top to bottom, 1) multiple view-specific fast LAB cascade for extremely quick face proposal, 2) multiple coarse MLP cascade for further candidate window verification, and 3) a unified fine MLP cascade with shape-indexed features for accurate face detection. Compared with other structures, on the one hand, the proposed one uses multiple computationally efficient distributed classifiers to propose a small number of candidate windows but with a high recall of multi-view faces. On the other hand, by using a unified MLP cascade to examine proposals of all views in a centralized style, it provides a favorable solution for multi-view face detection with high accuracy and low time-cost. Besides, the FuSt detector is alignment-aware and performs a coarse facial part prediction which is beneficial for subsequent face alignment. Extensive experiments on two challenging datasets, FDDB and AFW, demonstrate the effectiveness of our FuSt detector in both accuracy and speed.

##### Abstract (translated by Google)
在开放的环境中进行多视角人脸检测是一项具有挑战性的任务，因为人脸外观和形状的多样化。大多数多视角人脸检测器依赖于多个模型，并行组织，金字塔或树形结构，这在精度和时间成本之间折中。针对更有利的多视角人脸检测器，提出了一种新颖的漏斗结构级联（FuSt）检测框架。我们的FuSt从上到下包含1）多视图特定的快速LAB级联，用于非常快速的人脸建议，2）用于进一步候选窗口验证的多个粗MLP级联，以及3）统一的精细MLP级联与形状索引功能，用于精确的人脸检测。与其他结构相比，提出的方法一方面使用多个计算效率较高的分布式分类器来提出少量的候选窗口，但对多视图人脸具有较高的召回率。另一方面，通过统一的MLP级联，集中式审视所有视图的提议，为高精度，低时间成本的多视角人脸检测提供了有利的解决方案。此外，FuSt检测器是对齐感知的并且执行粗略的面部部分预测，这对于随后的面部对准是有益的。对两个具有挑战性的数据集FDDB和AFW进行的大量实验证明了我们的FuSt检测器在精度和速度方面的有效性。

##### URL
[https://arxiv.org/abs/1609.07304](https://arxiv.org/abs/1609.07304)

##### PDF
[https://arxiv.org/pdf/1609.07304](https://arxiv.org/pdf/1609.07304)

