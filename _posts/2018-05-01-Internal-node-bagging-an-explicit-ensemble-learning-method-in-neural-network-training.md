---
layout: post
title: "Internal node bagging: an explicit ensemble learning method in neural network training"
date: 2018-05-01 07:16:24
categories: arXiv_AI
tags: arXiv_AI Inference
author: Shun Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel view to understand how dropout works as an inexplicit ensemble learning method, which do not point out how many and which nodes to learn a certain feature. We propose a new training method named internal node bagging, this method explicitly force a group of nodes to learn a certain feature in training time, and combine those nodes to be one node in inference time. It means we can use much more parameters to improve model's fitting ability in training time while keeping model small in inference time. We test our method on several benchmark datasets and find it significantly more efficiency than dropout on small model.

##### Abstract (translated by Google)
我们引入了一种新颖的观点来理解失落如何作为一种不明显的集合学习方法，它没有指出有多少节点和哪个节点学习某个特征。我们提出了一种新的训练方法 - 内部节点装袋方法，该方法明确地迫使一组节点在训练时间内学习一定的特征，并将这些节点组合成一个节点作为推理时间。这意味着我们可以使用更多的参数来提高模型在训练时间的拟合能力，同时保持模型在推理时间内的小。我们在几个基准数据集上测试了我们的方法，发现它比小模型上的辍学效率高得多。

##### URL
[https://arxiv.org/abs/1805.00215](https://arxiv.org/abs/1805.00215)

##### PDF
[https://arxiv.org/pdf/1805.00215](https://arxiv.org/pdf/1805.00215)

