---
layout: post
title: "Speaker-Follower Models for Vision-and-Language Navigation"
date: 2018-06-07 15:15:35
categories: arXiv_CV
tags: arXiv_CV
author: Daniel Fried, Ronghang Hu, Volkan Cirik, Anna Rohrbach, Jacob Andreas, Louis-Philippe Morency, Taylor Berg-Kirkpatrick, Kate Saenko, Dan Klein, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Navigation guided by natural language instructions presents a challenging reasoning problem for instruction followers. Natural language instructions typically identify only a few high-level decisions and landmarks rather than complete low-level motor behaviors; much of the missing information must be inferred based on perceptual context. In machine learning settings, this presents a double challenge: it is difficult to collect enough annotated data to enable learning of this reasoning process from scratch, and empirically difficult to implement the reasoning process using generic sequence models. Here we describe an approach to vision-and-language navigation that addresses both these issues with an embedded speaker model. We use this speaker model to synthesize new instructions for data augmentation and to implement pragmatic reasoning for evaluating candidate action sequences. Both steps are supported by a panoramic action space that reflects the granularity of human-generated instructions. Experiments show that all three pieces of this approach---speaker-driven data augmentation, pragmatic reasoning and panoramic action space---dramatically improve the performance of a baseline instruction follower, more than doubling the success rate over the best existing approach on a standard benchmark.

##### Abstract (translated by Google)
以自然语言指导为指导的导航为教学追随者提出了具有挑战性的推理问题。自然语言指令通常只识别少数高层决策和地标，而不是完成低层次的运动行为;大部分缺失的信息必须根据感知上下文来推断。在机器学习设置中，这提出了一个双重挑战：难以收集足够的注释数据以使得从头开始学习该推理过程，并且在经验上难以使用通用序列模型实施推理过程。这里我们介绍一种视觉和语言导航方法，用嵌入式扬声器模型解决这两个问题。我们使用这种说话人模型来综合数据增强的新指令，并实施用于评估候选动作序列的实用推理。这两个步骤都由全景动作空间支持，该动作空间反映了人为指令的粒度。实验表明，这种方法的三个部分---演讲者驱动的数据增强，实用推理和全景动作空间---显着提高了基线指令跟随者的性能，比现有最佳方法的成功率提高了一倍以上标准基准。

##### URL
[http://arxiv.org/abs/1806.02724](http://arxiv.org/abs/1806.02724)

##### PDF
[http://arxiv.org/pdf/1806.02724](http://arxiv.org/pdf/1806.02724)

