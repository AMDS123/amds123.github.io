---
layout: post
title: "Self-Supervised Video Representation Learning With Odd-One-Out Networks"
date: 2017-04-05 05:52:00
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Represenation_Learning Classification Recognition
author: Basura Fernando, Hakan Bilen, Efstratios Gavves, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new self-supervised CNN pre-training technique based on a novel auxiliary task called "odd-one-out learning". In this task, the machine is asked to identify the unrelated or odd element from a set of otherwise related elements. We apply this technique to self-supervised video representation learning where we sample subsequences from videos and ask the network to learn to predict the odd video subsequence. The odd video subsequence is sampled such that it has wrong temporal order of frames while the even ones have the correct temporal order. Therefore, to generate a odd-one-out question no manual annotation is required. Our learning machine is implemented as multi-stream convolutional neural network, which is learned end-to-end. Using odd-one-out networks, we learn temporal representations for videos that generalizes to other related tasks such as action recognition. On action classification, our method obtains 60.3\% on the UCF101 dataset using only UCF101 data for training which is approximately 10% better than current state-of-the-art self-supervised learning methods. Similarly, on HMDB51 dataset we outperform self-supervised state-of-the art methods by 12.7% on action classification task.

##### Abstract (translated by Google)
我们提出了一种新的自主监督的CNN预训练技术，它基于一种称为“奇怪的一次学习”的新辅助任务。在这个任务中，机器被要求从一组其他相关元素中识别不相关或奇怪的元素。我们将这种技术应用于自我监督的视频表示学习，我们从视频中采样子序列，并要求网络学习预测奇数视频子序列。对奇数视频子序列进行采样，使得它具有错误的帧时间顺序，而偶数子序列具有正确的时间顺序。因此，要生成一个奇怪的一个问题，不需要手动注释。我们的学习机被实现为多流卷积神经网络，这是学习端到端。使用奇数一出网络，我们学习视频的时间表示，推广到其他相关任务，如动作识别。在动作分类上，我们的方法在UCF101数据集上只用UCF101的数据获得了60.3％的训练数据，比当前最先进的自我监督的学习方法好了约10％。同样，在HMDB51数据集上，我们的行为分类任务的表现优于自我监督的最先进的方法12.7％。

##### URL
[https://arxiv.org/abs/1611.06646](https://arxiv.org/abs/1611.06646)

##### PDF
[https://arxiv.org/pdf/1611.06646](https://arxiv.org/pdf/1611.06646)

