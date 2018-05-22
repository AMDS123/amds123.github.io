---
layout: post
title: "Streaming MANN: A Streaming-Based Inference for Energy-Efficient Memory-Augmented Neural Networks"
date: 2018-05-21 10:34:22
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: Seongsik Park, Jaehee Jang, Seijoon Kim, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
With the successful development of artificial intelligence using deep learning, there has been growing interest in its deployment. The mobile environment is the closest hardware platform to real life, and it has become an important platform for the success or failure of artificial intelligence. Memory-augmented neural networks (MANNs) are neural networks proposed to efficiently handle question-and-answer (Q&A) tasks, well-suited for mobile devices. As a MANN requires various types of operations and recurrent data paths, it is difficult to accelerate the inference in the structure designed for other conventional neural network models, which is one of the biggest obstacles to deploying MANNs in mobile environments. To address the aforementioned issues, we propose Streaming MANN. This is the first attempt to implement and demonstrate the architecture for energy-efficient inference of MANNs with the concept of streaming processing. To achieve the full potential of the streaming process, we propose a novel approach, called inference thresholding, using Bayesian approach considering the characteristics of natural language processing (NLP) tasks. To evaluate our proposed approaches, we implemented the architecture and method in a field-programmable gate array (FPGA) which is suitable for streaming processing. We measured the execution time and power consumption of the inference for the bAbI dataset. The experimental results showed that the performance efficiency per energy (FLOPS/kJ) of the Streaming MANN increased by a factor of up to about 126 compared to the results of NVIDIA TITAN V, and up to 140 if inference thresholding is applied.

##### Abstract (translated by Google)
随着使用深度学习的人工智能的成功开发，人们对其部署的兴趣越来越大。移动环境是现实生活中距离最近的硬件平台，已成为人工智能成败的重要平台。记忆增强神经网络（MANNs）是提出的神经网络，用于高效地处理问答（Q＆A）任务，非常适合移动设备。由于MANN需要各种类型的操作和经常性的数据路径，因此很难加快为其他常规神经网络模型设计的结构的推理，这是在移动环境中部署MANNs的最大障碍之一。为了解决上述问题，我们提出流媒体MANN。这是第一次尝试和展示流式处理概念的MANN节能推断架构。为了实现流处理的全部潜力，我们提出了一种新的方法，称为推理阈值处理，考虑到自然语言处理（NLP）任务的特点，使用贝叶斯方法。为了评估我们提出的方法，我们在适用于流处理的现场可编程门阵列（FPGA）中实现了架构和方法。我们测量了bAbI数据集推断的执行时间和功耗。实验结果表明，与NVIDIA TITAN V的结果相比，Streaming MANN的单位能量性能效率（FLOPS / kJ）增加了126倍，如果采用推理阈值，效能增加了140倍。

##### URL
[https://arxiv.org/abs/1805.07978](https://arxiv.org/abs/1805.07978)

##### PDF
[https://arxiv.org/pdf/1805.07978](https://arxiv.org/pdf/1805.07978)

