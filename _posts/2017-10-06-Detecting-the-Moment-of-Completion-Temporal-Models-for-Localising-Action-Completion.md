---
layout: post
title: "Detecting the Moment of Completion: Temporal Models for Localising Action Completion"
date: 2017-10-06 08:30:05
categories: arXiv_CV
tags: arXiv_CV RNN Detection
author: Farnoosh Heidarivincheh, Majid Mirmehdi, Dima Damen
mathjax: true
---

* content
{:toc}

##### Abstract
Action completion detection is the problem of modelling the action's progression towards localising the moment of completion - when the action's goal is confidently considered achieved. In this work, we assess the ability of two temporal models, namely Hidden Markov Models (HMM) and Long-Short Term Memory (LSTM), to localise completion for six object interactions: switch, plug, open, pull, pick and drink. We use a supervised approach, where annotations of pre-completion and post-completion frames are available per action, and fine-tuned CNN features are used to train temporal models. Tested on the Action-Completion-2016 dataset, we detect completion within 10 frames of annotations for ~75% of completed action sequences using both temporal models. Results show that fine-tuned CNN features outperform hand-crafted features for localisation, and that observing incomplete instances is necessary when incomplete sequences are also present in the test set.

##### Abstract (translated by Google)
行动完成检测是将行动的进展建模为完成时刻定位的问题 - 当行动的目标被自信地认为已经实现时。在这项工作中，我们评估了两个时间模型的能力，即隐马尔可夫模型（HMM）和长期短期记忆（LSTM），以定位完成六个对象的交互：开关，插件，开放，拉，挑和饮料。我们使用监督的方法，每个动作都可以使用预完成和完成后帧的注释，并且使用微调的CNN特征来训练时间模型。在Action-Completion-2016数据集上进行测试，我们使用两个时间模型在约10帧的注释中检测完成约75％完成的动作序列。结果表明，微调的CNN特征胜过手工定位的特征，当测试集中还存在不完整的序列时，观察不完全的实例是必要的。

##### URL
[https://arxiv.org/abs/1710.02310](https://arxiv.org/abs/1710.02310)

##### PDF
[https://arxiv.org/pdf/1710.02310](https://arxiv.org/pdf/1710.02310)

