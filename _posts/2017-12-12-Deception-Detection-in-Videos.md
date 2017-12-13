---
layout: post
title: "Deception Detection in Videos"
date: 2017-12-12 18:16:43
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Prediction Detection Recognition
author: Zhe Wu, Bharat Singh, Larry S. Davis, V. S. Subrahmanian
mathjax: true
---

* content
{:toc}

##### Abstract
We present a system for covert automated deception detection in real-life courtroom trial videos. We study the importance of different modalities like vision, audio and text for this task. On the vision side, our system uses classifiers trained on low level video features which predict human micro-expressions. We show that predictions of high-level micro-expressions can be used as features for deception prediction. Surprisingly, IDT (Improved Dense Trajectory) features which have been widely used for action recognition, are also very good at predicting deception in videos. We fuse the score of classifiers trained on IDT features and high-level micro-expressions to improve performance. MFCC (Mel-frequency Cepstral Coefficients) features from the audio domain also provide a significant boost in performance, while information from transcripts is not very beneficial for our system. Using various classifiers, our automated system obtains an AUC of 0.877 (10-fold cross-validation) when evaluated on subjects which were not part of the training set. Even though state-of-the-art methods use human annotations of micro-expressions for deception detection, our fully automated approach outperforms them by 5%. When combined with human annotations of micro-expressions, our AUC improves to 0.922. We also present results of a user-study to analyze how well do average humans perform on this task, what modalities they use for deception detection and how they perform if only one modality is accessible. Our project page can be found at \url{this https URL}.

##### Abstract (translated by Google)
我们提出了一个秘密自动欺骗检测系统在真实法庭审判视频。我们研究视觉，音频和文本等不同方式对于这项任务的重要性。在视觉方面，我们的系统使用经过低级别视频特征训练的分类器来预测人类微表情。我们表明，高级微表达式的预测可以用作欺骗预测的特征。令人惊讶的是，IDT（Improved Dense Trajectory）功能被广泛用于动作识别，也非常适合预测视频中的欺骗行为。我们融合了对IDT特性和高级微表达式进行训练的分类器得分，以提高性能。来自音频领域的MFCC（Mel频率倒谱系数）特性也提供了显着的性能提升，而来自转录本的信息对我们的系统并不是很有利。使用各种分类器，我们的自动化系统在对不属于训练集的对象进行评估时获得0.877的AUC（10倍交叉验证）。尽管最先进的方法使用人类对微表情的注释来进行欺骗检测，但是我们的全自动方法的表现优于5％。当与微表情的人注释相结合，我们的AUC提高到0.922。我们还介绍了一项用户研究的结果，以分析人类平均完成这项任务的能力，他们使用什么模式进行欺骗检测，以及如果只有一种模式可以访问，他们的表现如何。我们的项目页面可以在\ url {this https URL}找到。

##### URL
[https://arxiv.org/abs/1712.04415](https://arxiv.org/abs/1712.04415)

##### PDF
[https://arxiv.org/pdf/1712.04415](https://arxiv.org/pdf/1712.04415)

