---
layout: post
title: "HC-Net: Memory-based Incremental Dual-Network System for Continual learning"
date: 2018-09-07 12:39:13
categories: arXiv_AI
tags: arXiv_AI Classification
author: Jangho Kim, Jeesoo Kim, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Training a neural network for a classification task typically assumes that the data to train are given from the beginning. However, in the real world, additional data accumulate gradually and the model requires additional training without accessing the old training data. This usually leads to the catastrophic forgetting problem which is inevitable for the traditional training methodology of neural networks. In this paper, we propose a memory-based continual learning method that is able to learn additional tasks while retaining the performance of previously learned tasks. Composed of two complementary networks, the Hippocampus-net (H-net) and the Cortex-net (C-net), our model estimates the index of the corresponding task for an input sample and utilizes a particular portion of itself with the estimated index. The C-net guarantees no degradation in the performance of the previously learned tasks and the H-net shows high confidence in finding the origin of the input sample

##### Abstract (translated by Google)
为分类任务训练神经网络通常假设从头开始给出要训练的数据。然而，在现实世界中，附加数据逐渐累积，并且模型需要额外的训练而无需访问旧的训练数据。这通常会导致灾难性的遗忘问题，这对传统的神经网络训练方法来说是不可避免的。在本文中，我们提出了一种基于记忆的连续学习方法，该方法能够在保留先前学习任务的性能的同时学习其他任务。我们的模型由两个互补网络组成，即Hippocampus-net（H-net）和Cortex-net（C-net），我们的模型估计输入样本的相应任务的索引，并利用其自身的特定部分和估计的索引。 C-net保证先前学习的任务的性能不会降低，并且H-net显示出找到输入样本的原点的高可信度

##### URL
[http://arxiv.org/abs/1809.02441](http://arxiv.org/abs/1809.02441)

##### PDF
[http://arxiv.org/pdf/1809.02441](http://arxiv.org/pdf/1809.02441)

