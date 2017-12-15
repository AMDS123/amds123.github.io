---
layout: post
title: "A Compositional Approach to Language Modeling"
date: 2016-04-01 01:51:34
categories: arXiv_SD
tags: arXiv_SD Language_Model
author: Kushal Arora, Anand Rangarajan
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional language models treat language as a finite state automaton on a probability space over words. This is a very strong assumption when modeling something inherently complex such as language. In this paper, we challenge this by showing how the linear chain assumption inherent in previous work can be translated into a sequential composition tree. We then propose a new model that marginalizes over all possible composition trees thereby removing any underlying structural assumptions. As the partition function of this new model is intractable, we use a recently proposed sentence level evaluation metric Contrastive Entropy to evaluate our model. Given this new evaluation metric, we report more than 100% improvement across distortion levels over current state of the art recurrent neural network based language models.

##### Abstract (translated by Google)
传统的语言模型把语言视为一个概率空间上的有限状态自动机。在对语言等固有复杂的东西进行建模时，这是一个非常有力的假设。在本文中，我们通过展示以前工作中固有的线性链假设如何转化为顺序合成树来挑战这一点。然后，我们提出一个新的模型，边缘化所有可能的组合树，从而消除任何潜在的结构性假设。由于这个新模型的分割函数是难以处理的，我们使用最近提出的句子层次评价度量对比熵来评价我们的模型。考虑到这个新的评估指标，我们报告了超过现有技术的基于递归神经网络的语言模型的失真水平超过100％的改善。

##### URL
[https://arxiv.org/abs/1604.00100](https://arxiv.org/abs/1604.00100)

##### PDF
[https://arxiv.org/pdf/1604.00100](https://arxiv.org/pdf/1604.00100)

