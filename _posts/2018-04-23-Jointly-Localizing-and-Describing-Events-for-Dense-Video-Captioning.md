---
layout: post
title: "Jointly Localizing and Describing Events for Dense Video Captioning"
date: 2018-04-23 08:18:35
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Optimization Detection
author: Yehao Li, Ting Yao, Yingwei Pan, Hongyang Chao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically describing a video with natural language is regarded as a fundamental challenge in computer vision. The problem nevertheless is not trivial especially when a video contains multiple events to be worthy of mention, which often happens in real videos. A valid question is how to temporally localize and then describe events, which is known as "dense video captioning." In this paper, we present a novel framework for dense video captioning that unifies the localization of temporal event proposals and sentence generation of each proposal, by jointly training them in an end-to-end manner. To combine these two worlds, we integrate a new design, namely descriptiveness regression, into a single shot detection structure to infer the descriptive complexity of each detected proposal via sentence generation. This in turn adjusts the temporal locations of each event proposal. Our model differs from existing dense video captioning methods since we propose a joint and global optimization of detection and captioning, and the framework uniquely capitalizes on an attribute-augmented video captioning architecture. Extensive experiments are conducted on ActivityNet Captions dataset and our framework shows clear improvements when compared to the state-of-the-art techniques. More remarkably, we obtain a new record: METEOR of 12.96% on ActivityNet Captions official test set.

##### Abstract (translated by Google)
使用自然语言自动描述视频被视为计算机视觉中的基本挑战。然而，问题并非微不足道，尤其是当视频包含值得一提的多个事件时，这些事件通常发生在真实视频中。一个有效的问题是如何暂时本地化然后描述事件，这被称为“密集视频字幕”。在本文中，我们提出了一个新的密集视频字幕框架，通过以端到端的方式联合训练，统一时间事件提议的本地化和每个提案的句子生成。为了将这两个世界结合起来，我们将新设计（即描述性回归）整合到单个镜头检测结构中，以通过句子生成来推断每个检测到的提议的描述复杂性。这反过来调整每个事件提议的时间位置。我们的模型与现有的密集视频字幕方法不同，因为我们提出了检测和字幕的联合和全局优化，并且该框架独特地利用属性增强的视频字幕体系结构。在ActivityNet Captions数据集上进行了大量实验，与最先进的技术相比，我们的框架显示出明显的改进。更值得注意的是，我们获得了一项新记录：ActivityNet Captions官方测试集的METEOR为12.96％。

##### URL
[https://arxiv.org/abs/1804.08274](https://arxiv.org/abs/1804.08274)

##### PDF
[https://arxiv.org/pdf/1804.08274](https://arxiv.org/pdf/1804.08274)

