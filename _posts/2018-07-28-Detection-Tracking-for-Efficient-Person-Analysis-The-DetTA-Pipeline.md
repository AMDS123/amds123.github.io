---
layout: post
title: "Detection-Tracking for Efficient Person Analysis: The DetTA Pipeline"
date: 2018-07-28 10:33:47
categories: arXiv_CV
tags: arXiv_CV Tracking Deep_Learning Prediction Detection
author: Stefan Breuers, Lucas Beyer, Umer Rafi, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
In the past decade many robots were deployed in the wild, and people detection and tracking is an important component of such deployments. On top of that, one often needs to run modules which analyze persons and extract higher level attributes such as age and gender, or dynamic information like gaze and pose. The latter ones are especially necessary for building a reactive, social robot-person interaction. 
 In this paper, we combine those components in a fully modular detection-tracking-analysis pipeline, called DetTA. We investigate the benefits of such an integration on the example of head and skeleton pose, by using the consistent track ID for a temporal filtering of the analysis modules' observations, showing a slight improvement in a challenging real-world scenario. We also study the potential of a so-called "free-flight" mode, where the analysis of a person attribute only relies on the filter's predictions for certain frames. Here, our study shows that this boosts the runtime dramatically, while the prediction quality remains stable. This insight is especially important for reducing power consumption and sharing precious (GPU-)memory when running many analysis components on a mobile platform, especially so in the era of expensive deep learning methods.

##### Abstract (translated by Google)
在过去十年中，许多机器人被部署在野外，人员检测和跟踪是此类部署的重要组成部分。最重要的是，人们经常需要运行模块来分析人员并提取更高级别的属性，如年龄和性别，或动态信息，如凝视和姿势。后者对于建立被动的社交机器人 - 人交互尤其必要。
 在本文中，我们将这些组件组合在一个完全模块化的检测跟踪分析管道中，称为DetTA。我们通过使用一致的轨道ID对分析模块的观察进行时间过滤来研究这种集成对头部和骨架姿势示例的好处，显示在具有挑战性的现实场景中略有改进。我们还研究了所谓的“自由飞行”模式的潜力，其中人物属性的分析仅依赖于过滤器对某些帧的预测。在这里，我们的研究表明，这会显着提高运行时间，同时预测质量保持稳定。当在移动平台上运行许多分析组件时，这种洞察对于降低功耗和共享宝贵的（GPU）内存尤为重要，尤其是在昂贵的深度学习方法时代。

##### URL
[http://arxiv.org/abs/1804.10134](http://arxiv.org/abs/1804.10134)

##### PDF
[http://arxiv.org/pdf/1804.10134](http://arxiv.org/pdf/1804.10134)

