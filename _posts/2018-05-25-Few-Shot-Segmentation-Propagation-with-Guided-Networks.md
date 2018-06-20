---
layout: post
title: "Few-Shot Segmentation Propagation with Guided Networks"
date: 2018-05-25 17:02:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization Inference
author: Kate Rakelly, Evan Shelhamer, Trevor Darrell, Alexei A. Efros, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based methods for visual segmentation have made progress on particular types of segmentation tasks, but are limited by the necessary supervision, the narrow definitions of fixed tasks, and the lack of control during inference for correcting errors. To remedy the rigidity and annotation burden of standard approaches, we address the problem of few-shot segmentation: given few image and few pixel supervision, segment any images accordingly. We propose guided networks, which extract a latent task representation from any amount of supervision, and optimize our architecture end-to-end for fast, accurate few-shot segmentation. Our method can switch tasks without further optimization and quickly update when given more guidance. We report the first results for segmentation from one pixel per concept and show real-time interactive video segmentation. Our unified approach propagates pixel annotations across space for interactive segmentation, across time for video segmentation, and across scenes for semantic segmentation. Our guided segmentor is state-of-the-art in accuracy for the amount of annotation and time. See <a href="http://github.com/shelhamer/revolver">this http URL</a> for code, models, and more details.

##### Abstract (translated by Google)
用于视觉分割的基于学习的方法已经在特定类型的分割任务上取得了进展，但受到必要的监督，固定任务的狭义定义以及在纠正错误推理期间缺乏控制的限制。为了弥补标准方法的严格性和标注负担，我们解决了少镜头分割的问题：给出少量图像和少量像素监督，相应地分割任何图像。我们提出了引导式网络，它从任何监督量中提取潜在的任务表示，并优化我们的体系结构，实现快速，准确的少镜头分割。我们的方法可以在没有进一步优化的情况下切换任务，并在提供更多指导时快速更我们从每个概念的一个像素报告第一个分割结果，并显示实时交互式视频分割。我们的统一方法跨越空间传播像素注释以进行交互式分割，跨视频分割的时间以及跨场景进行语义分割。我们的引导式分割器在注释量和时间精度方面达到了最先进的水平。有关代码，模型和更多详细信息，请参阅<a href="http://github.com/shelhamer/revolver">此http URL </a>。

##### URL
[http://arxiv.org/abs/1806.07373](http://arxiv.org/abs/1806.07373)

##### PDF
[http://arxiv.org/pdf/1806.07373](http://arxiv.org/pdf/1806.07373)

