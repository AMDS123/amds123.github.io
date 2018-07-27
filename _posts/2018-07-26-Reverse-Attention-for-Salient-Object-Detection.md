---
layout: post
title: "Reverse Attention for Salient Object Detection"
date: 2018-07-26 03:30:57
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Attention CNN Deep_Learning Prediction Detection
author: Shuhan Chen, Xiuli Tan, Ben Wang, Xuelong Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Benefit from the quick development of deep learning techniques, salient object detection has achieved remarkable progresses recently. However, there still exists following two major challenges that hinder its application in embedded devices, low resolution output and heavy model weight. To this end, this paper presents an accurate yet compact deep network for efficient salient object detection. More specifically, given a coarse saliency prediction in the deepest layer, we first employ residual learning to learn side-output residual features for saliency refinement, which can be achieved with very limited convolutional parameters while keep accuracy. Secondly, we further propose reverse attention to guide such side-output residual learning in a top-down manner. By erasing the current predicted salient regions from side-output features, the network can eventually explore the missing object parts and details which results in high resolution and accuracy. Experiments on six benchmark datasets demonstrate that the proposed approach compares favorably against state-of-the-art methods, and with advantages in terms of simplicity, efficiency (45 FPS) and model size (81 MB).

##### Abstract (translated by Google)
受益于深度学习技术的快速发展，显着对象检测最近取得了显着进展。然而，仍然存在以下两个主要挑战，这些挑战阻碍了其在嵌入式设备中的应用，低分辨率输出和重型模型重量。为此，本文提出了一种准确而紧凑的深度网络，用于高效的显着物体检测。更具体地，给定最深层中的粗略显着性预测，我们首先使用残差学习来学习用于显着性细化的侧输出残差特征，这可以利用非常有限的卷积参数来实现，同时保持准确性。其次，我们进一步提出反向关注以自上而下的方式引导这种侧输出残差学习。通过从侧输出特征中擦除当前预测的显着区域，网络最终可以探索丢失的对象部分和细节，从而产生高分辨率和准确性。对六个基准数据集的实验表明，所提出的方法优于现有技术方法，并且在简单性，效率（45 FPS）和模型大小（81 MB）方面具有优势。

##### URL
[http://arxiv.org/abs/1807.09940](http://arxiv.org/abs/1807.09940)

##### PDF
[http://arxiv.org/pdf/1807.09940](http://arxiv.org/pdf/1807.09940)

