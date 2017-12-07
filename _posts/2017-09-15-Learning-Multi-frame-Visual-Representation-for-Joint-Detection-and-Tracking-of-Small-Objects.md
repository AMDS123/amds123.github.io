---
layout: post
title: "Learning Multi-frame Visual Representation for Joint Detection and Tracking of Small Objects"
date: 2017-09-15 04:48:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN RNN Detection Memory_Networks
author: Ryota Yoshihashi, Tu Tuan Trinh, Rei Kawakami, Shaodi You, Makoto Iida, Takeshi Naemura
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional and recurrent neural networks have delivered significant advancements in object detection and tracking. However, current models handle detection and tracking through separate networks, and deep-learning-based joint detection and tracking has not yet been explored despite its potential benefits to both tasks. In this study, we present an integrated neural model called the Recurrent Correlational Network for joint detection and tracking, where the two tasks are performed over multi-frame representation learned through a single, trainable, and end-to-end network. Detection is benefited by the tracker because of the stabilized trajectories and tracking is aided by the enhanced representation afforded by the training of the detector. We show that recently developed convolutional long short-term memory networks can learn multi-frame, multi-task representation, which is useful for both tasks. In experiments, we tackled the detection of small flying objects, such as birds and unmanned aerial vehicles, that can be challenging for single-frame-based detectors. We found that there was consistent improvement in detection performance by the proposed model in comparison with deep single-frame detectors and currently used motion-based detectors.

##### Abstract (translated by Google)
深卷积和递归神经网络已经在物体检测和跟踪方面取得了显着的进步。然而，目前的模型通过单独的网络来处理检测和跟踪，而基于深度学习的联合检测和跟踪尽管对两种任务都有潜在的益处，但还没有被探索。在这项研究中，我们提出了一个集成神经网络模型，称为复发相关网络联合检测和跟踪，其中两个任务是通过一个单一的，可训练的和端到端的网络学习的多帧表示。由于稳定的轨迹，跟踪器使检测受益，并且通过检测器的训练提供的增强的表示来辅助跟踪。我们表明，最近开发的卷积长短期记忆网络可以学习多帧，多任务表示，这对于这两个任务都是有用的。在实验中，我们处理了检测小型飞行物体，例如鸟类和无人机，这对单帧检测器来说可能是一个挑战。我们发现，与深度单帧检测器和目前使用的基于运动的检测器相比，所提出的模型在检测性能方面具有一致的改进。

##### URL
[https://arxiv.org/abs/1709.04666](https://arxiv.org/abs/1709.04666)

##### PDF
[https://arxiv.org/pdf/1709.04666](https://arxiv.org/pdf/1709.04666)

