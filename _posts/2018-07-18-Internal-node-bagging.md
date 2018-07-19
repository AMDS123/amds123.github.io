---
layout: post
title: "Internal node bagging"
date: 2018-07-18 03:00:08
categories: arXiv_AI
tags: arXiv_AI Inference
author: Shun Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel view to understand how dropout works as an inexplicit ensemble learning method, which doesn't point out how many and which nodes to learn a certain feature. We propose a new training method named internal node bagging, it explicitly forces a group of nodes to learn a certain feature in training time, and combine those nodes to be one node in inference time. It means we can use much more parameters to improve model's fitting ability in training time while keeping model small in inference time. We test our method on several benchmark datasets and find it performs significantly better than dropout on small models.

##### Abstract (translated by Google)
我们引入一种新颖的观点来理解辍学如何作为一种不明确的集成学习方法，它没有指出学习某个特征的节点数和节点数。我们提出了一种名为内部节点包装的新训练方法，它明确地迫使一组节点在训练时间内学习某个特征，并将这些节点组合成推理时间中的一个节点。这意味着我们可以使用更多的参数来提高模型在训练时间的拟合能力，同时保持模型在推理时间较小。我们在几个基准数据集上测试我们的方法，发现它在小型模型上的性能明显优于丢失。

##### URL
[http://arxiv.org/abs/1805.00215](http://arxiv.org/abs/1805.00215)

##### PDF
[http://arxiv.org/pdf/1805.00215](http://arxiv.org/pdf/1805.00215)

