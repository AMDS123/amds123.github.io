---
layout: post
title: "Accelerated Reinforcement Learning for Sentence Generation by Vocabulary Prediction"
date: 2018-09-05 19:11:14
categories: arXiv_CL
tags: arXiv_CL Image_Caption Reinforcement_Learning Caption Prediction
author: Kazuma Hashimoto, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
A major obstacle in reinforcement learning-based sentence generation is the large action space whose size is equal to the vocabulary size of the target-side language. To improve the efficiency of reinforcement learning, we present a novel approach for reducing the action space based on dynamic vocabulary prediction. Our method first predicts a fixed-size small vocabulary for each input to generate its target sentence. The input-specific vocabularies are then used at supervised and reinforcement learning steps, and also at test time. In our experiments on six machine translation and two image captioning datasets, our method achieves faster reinforcement learning ($\sim$2.7x faster) with much less GPU memory ($\sim$10x less) than the full-vocabulary counterpart. The reinforcement learning with our method consistently leads to significant improvement of BLEU scores, and the scores are equal to or better than those of baselines using the full vocabularies, with faster decoding time ($\sim$3x faster) on CPUs.

##### Abstract (translated by Google)
基于强化学习的句子生成的主要障碍是大动作空间，其大小等于目标语言的词汇量。为了提高强化学习的效率，我们提出了一种基于动态词汇预测来减少动作空间的新方法。我们的方法首先预测每个输入的固定大小的小词汇量以生成其目标句子。然后，在监督和强化学习步骤以及测试时使用输入特定词汇表。在我们对六个机器翻译和两个图像字幕数据集的实验中，我们的方法实现了更快的强化学习（$ \ sim快2.7倍），而GPU内存（$ \ sim $ 10x less）比全词汇对应物少得多。使用我们的方法强化学习一致地导致BLEU分数的显着改善，并且得分等于或优于使用完整词汇表的基线，得分更快的解码时间（$ \ sim $ 3x更快）在CPU上。

##### URL
[http://arxiv.org/abs/1809.01694](http://arxiv.org/abs/1809.01694)

##### PDF
[http://arxiv.org/pdf/1809.01694](http://arxiv.org/pdf/1809.01694)

