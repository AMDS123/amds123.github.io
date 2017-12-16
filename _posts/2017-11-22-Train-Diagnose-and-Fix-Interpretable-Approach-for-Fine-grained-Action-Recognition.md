---
layout: post
title: "Train, Diagnose and Fix: Interpretable Approach for Fine-grained Action Recognition"
date: 2017-11-22 20:51:32
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Deep_Learning Recognition
author: Jingxuan Hou, Tae Soo Kim, Austin Reiter
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the growing discriminative capabilities of modern deep learning methods for recognition tasks, the inner workings of the state-of-art models still remain mostly black-boxes. In this paper, we propose a systematic interpretation of model parameters and hidden representations of Residual Temporal Convolutional Networks (Res-TCN) for action recognition in time-series data. We also propose a Feature Map Decoder as part of the interpretation analysis, which outputs a representation of model's hidden variables in the same domain as the input. Such analysis empowers us to expose model's characteristic learning patterns in an interpretable way. For example, through the diagnosis analysis, we discovered that our model has learned to achieve view-point invariance by implicitly learning to perform rotational normalization of the input to a more discriminative view. Based on the findings from the model interpretation analysis, we propose a targeted refinement technique, which can generalize to various other recognition models. The proposed work introduces a three-stage paradigm for model learning: training, interpretable diagnosis and targeted refinement. We validate our approach on skeleton based 3D human action recognition benchmark of NTU RGB+D. We show that the proposed workflow is an effective model learning strategy and the resulting Multi-stream Residual Temporal Convolutional Network (MS-Res-TCN) achieves the state-of-the-art performance on NTU RGB+D.

##### Abstract (translated by Google)
尽管现代深度学习方法对于识别任务的判别能力越来越强，但是最先进的模型的内部运作依然是黑箱。在本文中，我们提出了一个时间序列数据动作识别的模型参数和残差时间卷积网络（Res-TCN）隐藏表示的系统解释。我们还提出了一个特征映射解码器作为解释分析的一部分，它输出模型的隐藏变量在与输入相同的域中的表示。这种分析使我们能够以可解释的方式揭示模型的特征学习模式。例如，通过诊断分析，我们发现我们的模型已经学会了通过隐式地学习将输入的旋转归一化转换为更具辨别性的视图来实现视点不变性。基于模型解释分析的结果，提出了一种针对性的细化技术，可以推广到其他各种识别模型。拟议的工作引入了模型学习的三阶段范式：培训，可解释的诊断和有针对性的细化。我们验证了我们在NTU RGB + D基于骨骼的三维人体动作识别基准方面的方法。我们表明，提出的工作流程是一种有效的模型学习策略，并且由此产生的多流残余时域卷积网络（MS-Res-TCN）在NTU RGB + D上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1711.08502](https://arxiv.org/abs/1711.08502)

##### PDF
[https://arxiv.org/pdf/1711.08502](https://arxiv.org/pdf/1711.08502)

