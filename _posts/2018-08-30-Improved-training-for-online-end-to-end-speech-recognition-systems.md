---
layout: post
title: "Improved training for online end-to-end speech recognition systems"
date: 2018-08-30 19:39:17
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition RNN Recognition
author: Suyoun Kim, Michael L. Seltzer, Jinyu Li, Rui Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Achieving high accuracy with end-to-end speech recognizers requires careful parameter initialization prior to training. Otherwise, the networks may fail to find a good local optimum. This is particularly true for online networks, such as unidirectional LSTMs. Currently, the best strategy to train such systems is to bootstrap the training from a tied-triphone system. However, this is time consuming, and more importantly, is impossible for languages without a high-quality pronunciation lexicon. In this work, we propose an initialization strategy that uses teacher-student learning to transfer knowledge from a large, well-trained, offline end-to-end speech recognition model to an online end-to-end model, eliminating the need for a lexicon or any other linguistic resources. We also explore curriculum learning and label smoothing and show how they can be combined with the proposed teacher-student learning for further improvements. We evaluate our methods on a Microsoft Cortana personal assistant task and show that the proposed method results in a 19 % relative improvement in word error rate compared to a randomly-initialized baseline system.

##### Abstract (translated by Google)
使用端到端语音识别器实现高精度需要在训练之前仔细参数初始化。否则，网络可能无法找到良好的局部最优。对于在线网络尤其如此，例如单向LSTM。目前，训练此类系统的最佳策略是从绑定三音素系统引导训练。然而，这是耗时的，并且更重要的是，对于没有高质量发音词典的语言来说是不可能的。在这项工作中，我们提出了一种初始化策略，该策略使用师生学习将知识从大型，训练有素的离线端到端语音识别模型转移到在线端到端模型，从而消除了对词典或任何其他语言资源。我们还探索课程学习和标签平滑，并展示如何将它们与建议的师生学习相结合，以进一步改进。我们在Microsoft Cortana个人助理任务上评估我们的方法，并表明与随机初始化的基线系统相比，所提出的方法导致字错误率相对提高19％。

##### URL
[http://arxiv.org/abs/1711.02212](http://arxiv.org/abs/1711.02212)

##### PDF
[http://arxiv.org/pdf/1711.02212](http://arxiv.org/pdf/1711.02212)

