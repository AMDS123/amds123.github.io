---
layout: post
title: "Predicting Important Objects for Egocentric Video Summarization"
date: 2015-05-18 20:07:20
categories: arXiv_CV
tags: arXiv_CV Salient Summarization Prediction Detection
author: Yong Jae Lee, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a video summarization approach for egocentric or "wearable" camera data. Given hours of video, the proposed method produces a compact storyboard summary of the camera wearer's day. In contrast to traditional keyframe selection techniques, the resulting summary focuses on the most important objects and people with which the camera wearer interacts. To accomplish this, we develop region cues indicative of high-level saliency in egocentric video---such as the nearness to hands, gaze, and frequency of occurrence---and learn a regressor to predict the relative importance of any new region based on these cues. Using these predictions and a simple form of temporal event detection, our method selects frames for the storyboard that reflect the key object-driven happenings. We adjust the compactness of the final summary given either an importance selection criterion or a length budget; for the latter, we design an efficient dynamic programming solution that accounts for importance, visual uniqueness, and temporal displacement. Critically, the approach is neither camera-wearer-specific nor object-specific; that means the learned importance metric need not be trained for a given user or context, and it can predict the importance of objects and people that have never been seen previously. Our results on two egocentric video datasets show the method's promise relative to existing techniques for saliency and summarization.

##### Abstract (translated by Google)
我们提出了一个以自我为中心或“可穿戴”相机数据的视频摘要方法。给定数小时的视频，提出的方法产生一个相机佩戴者的一天的紧凑的故事情节摘要。与传统的关键帧选择技术相比，所得到的总结集中在相机佩戴者与之交互的最重要的物体和人物上。为了做到这一点，我们开发了以自我为中心的视频中的高级显着性的区域线索，例如手的接近度，凝视和发生的频率，并学习一个回归因子来预测任何新的区域的相对重要性在这些暗示。使用这些预测和简单形式的时间事件检测，我们的方法为故事板选择反映关键对象驱动事件的帧。我们根据重要性选择标准或长度预算调整最终摘要的紧凑性;对于后者，我们设计了一个高效的动态规划解决方案，考虑到重要性，视觉唯一性和时间位移。重要的是，这种方法既不是照相机佩戴者特定的，也不是特定于对象的;这意味着学习重要性度量不需要针对给定的用户或上下文进行训练，并且可以预测之前从未见过的对象和人的重要性。我们在两个以自我为中心的视频数据集上的结果显示了该方法相对于现有技术的显着性和总结性的承诺。

##### URL
[https://arxiv.org/abs/1505.04803](https://arxiv.org/abs/1505.04803)

##### PDF
[https://arxiv.org/pdf/1505.04803](https://arxiv.org/pdf/1505.04803)

