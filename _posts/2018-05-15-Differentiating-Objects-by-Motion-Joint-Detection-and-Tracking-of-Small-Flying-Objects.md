---
layout: post
title: "Differentiating Objects by Motion: Joint Detection and Tracking of Small Flying Objects"
date: 2018-05-15 05:38:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Detection Relation
author: Ryota Yoshihashi, Tu Tuan Trinh, Rei Kawakami, Shaodi You, Makoto Iida, Takeshi Naemura
mathjax: true
---

* content
{:toc}

##### Abstract
While generic object detection has achieved large improvements with rich feature hierarchies from deep nets, detecting small objects with poor visual cues remains challenging. Motion cues from multiple frames may be more informative for detecting such hard-to-distinguish objects in each frame. However, how to encode discriminative motion patterns, such as deformations and pose changes that characterize objects, has remained an open question. To learn them and thereby realize small object detection, we present a neural model called the Recurrent Correlational Network, where detection and tracking are jointly performed over a multi-frame representation learned through a single, trainable, and end-to-end network. A convolutional long short-term memory network is utilized for learning informative appearance change for detection, while learned representation is shared in tracking for enhancing its performance. In experiments with datasets containing images of scenes with small flying objects, such as birds and unmanned aerial vehicles, the proposed method yielded consistent improvements in detection performance over deep single-frame detectors and existing motion-based detectors. Furthermore, our network performs as well as state-of-the-art generic object trackers when it was evaluated as a tracker on the bird dataset.

##### Abstract (translated by Google)
虽然通用对象检测通过深层网络的丰富特征层次结构取得了很大改进，但检测视觉线索不佳的小对象仍然具有挑战性。来自多个帧的运动提示可能对于在每个帧中检测这种难以区分的对象更具信息性。但是，如何编码区分运动模式，如表征物体的变形和姿态变化，仍然是一个悬而未决的问题。为了学习它们并从而实现小物体检测，我们提出了一种叫做递归相关网络的神经模型，其中检测和跟踪是通过单个可训练和端到端网络学习的多帧表示共同执行的。利用卷积长的短期记忆网络来学习信息外观变化以用于检测，而学习表示在追踪中被共享以提高其性能。在对含有小型飞行物体场景图像（如鸟类和无人机）的数据集进行的实验中，所提出的方法在深度单帧检测器和现有的基于运动的检测器的检测性能方面取得了一致的改进。此外，当我们的网络被评估为鸟类数据集上的跟踪器时，它的性能与最先进的通用对象跟踪器相当。

##### URL
[http://arxiv.org/abs/1709.04666](http://arxiv.org/abs/1709.04666)

##### PDF
[http://arxiv.org/pdf/1709.04666](http://arxiv.org/pdf/1709.04666)

