---
layout: post
title: "Sense Embedding Learning for Word Sense Induction"
date: 2016-06-22 04:59:08
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding
author: Linfeng Song, Zhiguo Wang, Haitao Mi, Daniel Gildea
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional word sense induction (WSI) methods usually represent each instance with discrete linguistic features or cooccurrence features, and train a model for each polysemous word individually. In this work, we propose to learn sense embeddings for the WSI task. In the training stage, our method induces several sense centroids (embedding) for each polysemous word. In the testing stage, our method represents each instance as a contextual vector, and induces its sense by finding the nearest sense centroid in the embedding space. The advantages of our method are (1) distributed sense vectors are taken as the knowledge representations which are trained discriminatively, and usually have better performance than traditional count-based distributional models, and (2) a general model for the whole vocabulary is jointly trained to induce sense centroids under the mutlitask learning framework. Evaluated on SemEval-2010 WSI dataset, our method outperforms all participants and most of the recent state-of-the-art methods. We further verify the two advantages by comparing with carefully designed baselines.

##### Abstract (translated by Google)
传统的词义感应（WSI）方法通常用离散的语言特征或共生特征来表示每个实例，并且为每个多义词单独训练一个模型。在这项工作中，我们建议学习WSI任务的感觉嵌入。在训练阶段，我们的方法为每个多义词引入多个感知质心（嵌入）。在测试阶段，我们的方法将每个实例表示为上下文向量，并通过在嵌入空间中找到最近的感知质心来引起其感觉。我们的方法的优点是：（1）分布式感知向量被认为是被区分地训练的知识表示，并且通常具有比传统的基于计数的分布式模型更好的性能;以及（2）整体词汇的通用模型被联合训练在mutlitask学习框架下诱导感知质心。在SemEval-2010 WSI数据集上进行评估，我们的方法胜过了所有参与者以及最近的大多数最先进的方法。通过与精心设计的基线进行比较，我们进一步验证了两个优点。

##### URL
[https://arxiv.org/abs/1606.05409](https://arxiv.org/abs/1606.05409)

##### PDF
[https://arxiv.org/pdf/1606.05409](https://arxiv.org/pdf/1606.05409)

