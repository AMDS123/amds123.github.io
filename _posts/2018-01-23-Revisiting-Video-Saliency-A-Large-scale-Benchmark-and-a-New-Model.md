---
layout: post
title: "Revisiting Video Saliency: A Large-scale Benchmark and a New Model"
date: 2018-01-23 08:01:50
categories: arXiv_CV
tags: arXiv_CV Salient Attention RNN
author: Wenguan Wang, Jianbing Shen, Fang Guo, Ming-Ming Cheng, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we contribute to video saliency research in two ways. First, we introduce a new benchmark for predicting human eye movements during dynamic scene free-viewing, which is long-time urged in this field. Our dataset, named DHF1K (Dynamic Human Fixation), consists of 1K high-quality, elaborately selected video sequences spanning a large range of scenes, viewpoints, motions, object types and background complexity. Existing video saliency datasets lack variety and generality of common dynamic scenes and fall short in covering challenging situations in unconstrained environments. In contrast, DHF1K makes a significant leap in terms of scalability, diversity and difficulty, and is expected to boost video saliency modeling. Second, we propose a novel video saliency model that augments the CNN-LSTM network architecture with an attention mechanism to enable fast, end-to-end saliency learning. The attention mechanism explicitly encodes static saliency information, thus allowing LSTM to focus on learning more flexible temporal saliency representation across successive frames. Such a design fully leverages existing large-scale static fixation datasets, avoids overfitting, and significantly improves training efficiency and testing performance. We thoroughly examine the performance of our model, with respect to the state of the art saliency models, on three large-scale datasets (i.e., DHF1K, Hollywood2, UCF sports). Experimental results over more than 1.2K testing videos containing 400K frames demonstrate that our model outperforms other competitors.

##### Abstract (translated by Google)
在这项工作中，我们以两种方式为视频显着性研究作出贡献。首先，我们介绍了一个在动态场景自由观看中预测人眼动作的新基准，这在这个领域已经有很长时间了。我们的数据集名为DHF1K（动态人体固定），由1K高质量精心挑选的视频序列组成，这些视频序列涵盖了大量场景，视点，运动，对象类型和背景复杂度。现有的视频显着性数据集缺乏常见动态场景的多样性和普遍性，并且在无约束环境中覆盖具有挑战性的情况方面存在缺陷。相比之下，DHF1K在可扩展性，多样性和难度方面有了重大飞跃，有望推动视频显着性建模。其次，我们提出了一种新颖的视频显着性模型，用CNN-LSTM网络架构来增强注意机制，以实现快速，端到端的显着性学习。注意机制明确地编码静态显着性信息，从而允许LSTM专注于学习跨越连续帧的更灵活的时间显着性表示。这样的设计充分利用了现有的大型静态固定数据集，避免了过度拟合，显着提高了培训效率和测试性能。我们在三个大型数据集（即DHF1K，好莱坞2，UCF体育）上彻底检查了我们的模型的性能，相对于最先进的显着性模型。在包含400K帧的超过1.2K个测试视频的实验结果表明，我们的模型胜过其他竞争对手。

##### URL
[http://arxiv.org/abs/1801.07424](http://arxiv.org/abs/1801.07424)

##### PDF
[http://arxiv.org/pdf/1801.07424](http://arxiv.org/pdf/1801.07424)

