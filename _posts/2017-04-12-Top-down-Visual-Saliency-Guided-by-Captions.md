---
layout: post
title: "Top-down Visual Saliency Guided by Captions"
date: 2017-04-12 22:49:47
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption
author: Vasili Ramanishka, Abir Das, Jianming Zhang, Kate Saenko
---

* content
{:toc}

##### Abstract
Neural image/video captioning models can generate accurate descriptions, but their internal process of mapping regions to words is a black box and therefore difficult to explain. Top-down neural saliency methods can find important regions given a high-level semantic task such as object classification, but cannot use a natural language sentence as the top-down input for the task. In this paper, we propose Caption-Guided Visual Saliency to expose the region-to-word mapping in modern encoder-decoder networks and demonstrate that it is learned implicitly from caption training data, without any pixel-level annotations. Our approach can produce spatial or spatiotemporal heatmaps for both predicted captions, and for arbitrary query sentences. It recovers saliency without the overhead of introducing explicit attention layers, and can be used to analyze a variety of existing model architectures and improve their design. Evaluation on large-scale video and image datasets demonstrates that our approach achieves comparable captioning performance with existing methods while providing more accurate saliency heatmaps. Our code is available at visionlearninggroup.github.io/caption-guided-saliency/.

##### Abstract (translated by Google)
神经图像/视频字幕模型可以生成准确的描述，但是将它们映射到单词的内部过程是一个黑盒子，因此很难解释。自顶向下的神经显着方法可以找到重要的区域给予高级语义任务，如对象分类，但不能使用自然语言语句作为任务的自上而下的输入。在本文中，我们提出了Caption-Guided Visual Saliency来揭示现代编码器 - 解码器网络中的地区间信息映射，并证明它是从字幕训练数据中隐式地获知的，没有任何像素级的注释。我们的方法可以为预测字幕和任意查询语句产生空间或时空热图。它可以在不引入显式关注层的情况下恢复显着性，并可用于分析各种现有的模型架构并改进其设计。对大规模视频和图像数据集的评估表明，我们的方法在提供更准确的显着热点的同时，利用现有方法实现了可比较的字幕性能。我们的代码可以在visionlearninggroup.github.io/caption-guided-saliency/上找到。

##### URL
[https://arxiv.org/abs/1612.07360](https://arxiv.org/abs/1612.07360)

