---
layout: post
title: "FearNet: Brain-Inspired Model for Incremental Learning"
date: 2017-11-28 21:26:15
categories: arXiv_CV
tags: arXiv_CV
author: Ronald Kemker, Christopher Kanan
mathjax: true
---

* content
{:toc}

##### Abstract
Incremental class learning involves sequentially learning classes in bursts of examples from the same class. This violates the assumptions that underlie methods for training standard deep neural networks, and will cause them to suffer from catastrophic forgetting. Arguably, the best method for incremental class learning is iCaRL, but it requires storing training examples for each class, making it challenging to scale. Here, we propose FearNet for incremental class learning. FearNet is a generative model that does not store previous examples, making it memory efficient. FearNet uses a brain-inspired dual-memory system in which new memories are consolidated from a network for recent memories inspired by the mammalian hippocampal complex to a network for long-term storage inspired by medial prefrontal cortex. Memory consolidation is inspired by mechanisms that occur during sleep. FearNet also uses a module inspired by the basolateral amygdala for determining which memory system to use for recall. FearNet achieves state-of-the-art performance at incremental class learning on image (CIFAR-100, CUB-200) and audio classification (AudioSet) benchmarks.

##### Abstract (translated by Google)
增量式课堂学习包括连续学习同一班级的例子。这违背了建立标准深度神经网络的方法的假设，并且会导致它们遭受灾难性的遗忘。可以说，增量类学习的最佳方法是iCaRL，但是它需要为每个类存储训练样例，这使得难以规模化。在这里，我们提出了增量课程学习的FearNet。 FearNet是一个生成模型，不存储以前的例子，使其内存效率。 FearNet使用一个大脑启发的双记忆系统，在这个系统中，新的记忆从网络中整合到最近由哺乳动物海马复合体启发的记忆中，并由内侧前额叶皮层激发的长期存储网络。记忆巩固的灵感来自睡眠期间发生的机制。 FearNet还使用了一个受基底外侧杏仁核启发的模块来确定哪个记忆系统用于召回。 FearNet在图像增量级学习（CIFAR-100，CUB-200）和音频分类（AudioSet）基准测试中实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1711.10563](https://arxiv.org/abs/1711.10563)

##### PDF
[https://arxiv.org/pdf/1711.10563](https://arxiv.org/pdf/1711.10563)

