---
layout: post
title: "Straight to Shapes: Real-time Detection of Encoded Shapes"
date: 2017-07-05 17:25:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Embedding CNN Prediction Detection
author: Saumya Jetley, Michael Sapienza, Stuart Golodetz, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Current object detection approaches predict bounding boxes, but these provide little instance-specific information beyond location, scale and aspect ratio. In this work, we propose to directly regress to objects' shapes in addition to their bounding boxes and categories. It is crucial to find an appropriate shape representation that is compact and decodable, and in which objects can be compared for higher-order concepts such as view similarity, pose variation and occlusion. To achieve this, we use a denoising convolutional auto-encoder to establish an embedding space, and place the decoder after a fast end-to-end network trained to regress directly to the encoded shape vectors. This yields what to the best of our knowledge is the first real-time shape prediction network, running at ~35 FPS on a high-end desktop. With higher-order shape reasoning well-integrated into the network pipeline, the network shows the useful practical quality of generalising to unseen categories similar to the ones in the training set, something that most existing approaches fail to handle.

##### Abstract (translated by Google)
目前的对象检测方法可以预测边界框，但是除了位置，比例和纵横比之外，这些提供了很少的特定于实例的信息。在这项工作中，我们建议直接回归到物体的形状，除了它们的边界框和类别。找到一个紧凑且可解码的适当的形状表示是至关重要的，在这个表示中可以比较高阶概念，如视图相似性，姿态变化和遮挡。为了实现这个目的，我们使用去噪卷积自动编码器来建立嵌入空间，并且在快速的端到端网络被训练直接回归到编码的形状向量之后放置解码器。这就产生了我们所知道的第一个实时形状预测网络，在高端桌面上以〜35 FPS运行。将高阶形状推理与网络流水线良好融合，网络显示了对训练集中类似的看不见的类的泛化的有用实用质量，是大多数现有方法无法处理的。

##### URL
[https://arxiv.org/abs/1611.07932](https://arxiv.org/abs/1611.07932)

##### PDF
[https://arxiv.org/pdf/1611.07932](https://arxiv.org/pdf/1611.07932)

