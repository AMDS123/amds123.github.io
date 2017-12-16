---
layout: post
title: "FastMask: Segment Multi-scale Object Candidates in One Shot"
date: 2017-04-11 21:20:57
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference
author: Hexiang Hu, Shiyi Lan, Yuning Jiang, Zhimin Cao, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
Objects appear to scale differently in natural images. This fact requires methods dealing with object-centric tasks (e.g. object proposal) to have robust performance over variances in object scales. In the paper, we present a novel segment proposal framework, namely FastMask, which takes advantage of hierarchical features in deep convolutional neural networks to segment multi-scale objects in one shot. Innovatively, we adapt segment proposal network into three different functional components (body, neck and head). We further propose a weight-shared residual neck module as well as a scale-tolerant attentional head module for efficient one-shot inference. On MS COCO benchmark, the proposed FastMask outperforms all state-of-the-art segment proposal methods in average recall being 2~5 times faster. Moreover, with a slight trade-off in accuracy, FastMask can segment objects in near real time (~13 fps) with 800*600 resolution images, demonstrating its potential in practical applications. Our implementation is available on this https URL

##### Abstract (translated by Google)
对象看上去在自然图像中缩放比例不同。这个事实要求处理以对象为中心的任务的方法（例如，对象提议）在对象尺度上具有对于变化的强健性能。在本文中，我们提出了一个新的分段提议框架，即FastMask，它利用深度卷积神经网络中的分层特征来一次分割多尺度对象。创新地，我们将细分提案网络适应于三个不同的功能组件（身体，颈部和头部）。我们进一步提出了一个权重共享的残余颈部模块以及一个用于高效一次性推理的容忍尺度的注意力头部模块。在MS COCO基准测试中，所提出的FastMask优于所有最先进的分段建议方法，平均召回速度提高2〜5倍。此外，FastMask可以在精确度上稍作折衷，可以以近乎实时（〜13 fps）的分辨率将图像分割成800 * 600的分辨率图像，展示了其在实际应用中的潜力。我们的实施可在此https网址上找到

##### URL
[https://arxiv.org/abs/1612.08843](https://arxiv.org/abs/1612.08843)

##### PDF
[https://arxiv.org/pdf/1612.08843](https://arxiv.org/pdf/1612.08843)

