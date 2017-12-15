---
layout: post
title: "A Multi-scale Multiple Instance Video Description Network"
date: 2016-03-19 02:27:58
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Huijuan Xu, Subhashini Venugopalan, Vasili Ramanishka, Marcus Rohrbach, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Generating natural language descriptions for in-the-wild videos is a challenging task. Most state-of-the-art methods for solving this problem borrow existing deep convolutional neural network (CNN) architectures (AlexNet, GoogLeNet) to extract a visual representation of the input video. However, these deep CNN architectures are designed for single-label centered-positioned object classification. While they generate strong semantic features, they have no inherent structure allowing them to detect multiple objects of different sizes and locations in the frame. Our paper tries to solve this problem by integrating the base CNN into several fully convolutional neural networks (FCNs) to form a multi-scale network that handles multiple receptive field sizes in the original image. FCNs, previously applied to image segmentation, can generate class heat-maps efficiently compared to sliding window mechanisms, and can easily handle multiple scales. To further handle the ambiguity over multiple objects and locations, we incorporate the Multiple Instance Learning mechanism (MIL) to consider objects in different positions and at different scales simultaneously. We integrate our multi-scale multi-instance architecture with a sequence-to-sequence recurrent neural network to generate sentence descriptions based on the visual representation. Ours is the first end-to-end trainable architecture that is capable of multi-scale region processing. Evaluation on a Youtube video dataset shows the advantage of our approach compared to the original single-scale whole frame CNN model. Our flexible and efficient architecture can potentially be extended to support other video processing tasks.

##### Abstract (translated by Google)
为野外视频生成自然语言描述是一项具有挑战性的任务。大多数解决这个问题的最先进的方法借用现有的深度卷积神经网络（CNN）架构（AlexNet，GoogLeNet）来提取输入视频的视觉表示。然而，这些深度CNN架构是专为单标签居中对象分类而设计的。虽然它们产生了强大的语义特征，但是它们没有内在的结构，使得它们能够检测帧中不同大小和位置的多个对象。我们的论文试图通过将基本的CNN集成到几个完全卷积神经网络（FCN）中来解决这个问题，以形成在原始图像中处理多个感受野大小的多尺度网络。先前应用于图像分割的FCN与滑动窗口机制相比可以有效地生成类热图，并且可以轻松处理多个尺度。为了进一步处理多个对象和位置的模糊性，我们引入了多实例学习机制（MIL）来同时考虑不同位置和不同尺度的对象。我们将我们的多尺度多实例体系结构与序列到序列递归神经网络相结合，以基于视觉表示生成句子描述。我们是第一个能够进行多尺度区域处理的端到端可训练架构。对Youtube视频数据集的评估显示了我们的方法与原始单尺度整体CNN模型相比的优势。我们灵活而高效的体系结构可能会扩展以支持其他视频处理任务。

##### URL
[https://arxiv.org/abs/1505.05914](https://arxiv.org/abs/1505.05914)

##### PDF
[https://arxiv.org/pdf/1505.05914](https://arxiv.org/pdf/1505.05914)

