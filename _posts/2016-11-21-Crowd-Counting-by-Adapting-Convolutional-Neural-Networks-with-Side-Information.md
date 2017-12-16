---
layout: post
title: "Crowd Counting by Adapting Convolutional Neural Networks with Side Information"
date: 2016-11-21 12:09:06
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Di Kang, Debarun Dhar, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision tasks often have side information available that is helpful to solve the task. For example, for crowd counting, the camera perspective (e.g., camera angle and height) gives a clue about the appearance and scale of people in the scene. While side information has been shown to be useful for counting systems using traditional hand-crafted features, it has not been fully utilized in counting systems based on deep learning. In order to incorporate the available side information, we propose an adaptive convolutional neural network (ACNN), where the convolutional filter weights adapt to the current scene context via the side information. In particular, we model the filter weights as a low-dimensional manifold, parametrized by the side information, within the high-dimensional space of filter weights. With the help of side information and adaptive weights, the ACNN can disentangle the variations related to the side information, and extract discriminative features related to the current context. Since existing crowd counting datasets do not contain ground-truth side information, we collect a new dataset with the ground-truth camera angle and height as the side information. On experiments in crowd counting, the ACNN improves counting accuracy compared to a plain CNN with a similar number of parameters. We also apply ACNN to image deconvolution to show its potential effectiveness on other computer vision applications.

##### Abstract (translated by Google)
计算机视觉任务通常具有有助于解决任务的辅助信息。例如，对于人群计数，摄像机视角（例如摄像机角度和高度）给出关于场景中人物的外观和规模的线索。尽管辅助信息已被证明对统计使用传统手工特征的系统有用，但是在基于深度学习的系统计数方面还没有被充分利用。为了整合可用的边信息，我们提出了一种自适应卷积神经网络（ACNN），其中卷积滤波器权重通过边信息适应当前场景上下文。特别地，我们将滤波器权重模型化为在滤波器权重的高维空间内由边信息进行参数化的低维流形。在辅助信息和自适应权重的帮助下，ACNN可以解开与辅助信息相关的变化，并提取与当前上下文相关的判别特征。由于现有的人群统计数据集不包含地面真实侧面信息，因此我们收集一个新的数据集，地面真实摄像机角度和高度作为边界信息。在人群计数实验中，与具有相似参数数量的普通CNN相比，ACNN提高了计数精度。我们还将ACNN应用于图像解卷积以显示其在其他计算机视觉应用上的潜在有效性。

##### URL
[https://arxiv.org/abs/1611.06748](https://arxiv.org/abs/1611.06748)

##### PDF
[https://arxiv.org/pdf/1611.06748](https://arxiv.org/pdf/1611.06748)

