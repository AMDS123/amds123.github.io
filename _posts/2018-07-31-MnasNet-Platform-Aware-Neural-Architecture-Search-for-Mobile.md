---
layout: post
title: "MnasNet: Platform-Aware Neural Architecture Search for Mobile"
date: 2018-07-31 01:34:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Classification Detection
author: Mingxing Tan, Bo Chen, Ruoming Pang, Vijay Vasudevan, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Designing convolutional neural networks (CNN) models for mobile devices is challenging because mobile models need to be small and fast, yet still accurate. Although significant effort has been dedicated to design and improve mobile models on all three dimensions, it is challenging to manually balance these trade-offs when there are so many architectural possibilities to consider. In this paper, we propose an automated neural architecture search approach for designing resource-constrained mobile CNN models. We propose to explicitly incorporate latency information into the main objective so that the search can identify a model that achieves a good trade-off between accuracy and latency. Unlike in previous work, where mobile latency is considered via another, often inaccurate proxy (e.g., FLOPS), in our experiments, we directly measure real-world inference latency by executing the model on a particular platform, e.g., Pixel phones. To further strike the right balance between flexibility and search space size, we propose a novel factorized hierarchical search space that permits layer diversity throughout the network. Experimental results show that our approach consistently outperforms state-of-the-art mobile CNN models across multiple vision tasks. On the ImageNet classification task, our model achieves 74.0% top-1 accuracy with 76ms latency on a Pixel phone, which is 1.5x faster than MobileNetV2 (Sandler et al. 2018) and 2.4x faster than NASNet (Zoph et al. 2018) with the same top-1 accuracy. On the COCO object detection task, our model family achieves both higher mAP quality and lower latency than MobileNets.

##### Abstract (translated by Google)
为移动设备设计卷积神经网络（CNN）模型具有挑战性，因为移动模型需要小而快，但仍然准确。尽管已经致力于在所有三个维度上设计和改进移动模型，但是当需要考虑许多架构可能性时，手动平衡这些权衡是具有挑战性的。在本文中，我们提出了一种自动神经结构搜索方法，用于设计资源受限的移动CNN模型。我们建议将延迟信息明确地合并到主要目标中，以便搜索可以识别在准确性和延迟之间实现良好折衷的模型。与先前的工作不同，在先前的工作中，通过另一个（通常是不准确的）代理（例如，FLOPS）来考虑移动延迟，在我们的实验中，我们通过在特定平台（例如，Pixel电话）上执行模型来直接测量实际推断延迟。为了进一步在灵活性和搜索空间大小之间取得适当平衡，我们提出了一种新颖的分解分层搜索空间，允许整个网络中的层分集。实验结果表明，我们的方法在多个视觉任务中始终优于最先进的移动CNN模型。在ImageNet分类任务中，我们的模型在Pixel手机上实现了74.0％的前1精度，76ms延迟，比MobileNetV2快（1.500倍）（Sandler等2018年），比NASNet快2.4倍（Zoph等2018）具有相同的前1精度。在COCO对象检测任务中，我们的模型系列实现了比MobileNets更高的mAP质量和更低的延迟。

##### URL
[http://arxiv.org/abs/1807.11626](http://arxiv.org/abs/1807.11626)

##### PDF
[http://arxiv.org/pdf/1807.11626](http://arxiv.org/pdf/1807.11626)

