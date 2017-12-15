---
layout: post
title: "Modeling Context Between Objects for Referring Expression Understanding"
date: 2016-08-01 19:03:27
categories: arXiv_CV
tags: arXiv_CV RNN Relation
author: Varun K. Nagaraja, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Referring expressions usually describe an object using properties of the object and relationships of the object with other objects. We propose a technique that integrates context between objects to understand referring expressions. Our approach uses an LSTM to learn the probability of a referring expression, with input features from a region and a context region. The context regions are discovered using multiple-instance learning (MIL) since annotations for context objects are generally not available for training. We utilize max-margin based MIL objective functions for training the LSTM. Experiments on the Google RefExp and UNC RefExp datasets show that modeling context between objects provides better performance than modeling only object properties. We also qualitatively show that our technique can ground a referring expression to its referred region along with the supporting context region.

##### Abstract (translated by Google)
引用表达式通常使用对象的属性以及对象与其他对象的关系来描述对象。我们提出了一种整合对象之间的上下文来理解引用表达式的技术。我们的方法使用LSTM来学习引用表达式的概率，输入来自区域和上下文区域的特征。上下文区域是使用多实例学习（MIL）发现的，因为上下文对象的注释通常不可用于训练。我们利用基于最大余量的MIL目标函数来训练LSTM。 Google RefExp和UNC RefExp数据集上的实验显示，对象之间的建模上下文比仅对对象属性建模提供了更好的性能。我们还定性地表明，我们的技术可以将一个指称的区域与支持的上下文区域相提并论。

##### URL
[https://arxiv.org/abs/1608.00525](https://arxiv.org/abs/1608.00525)

##### PDF
[https://arxiv.org/pdf/1608.00525](https://arxiv.org/pdf/1608.00525)

