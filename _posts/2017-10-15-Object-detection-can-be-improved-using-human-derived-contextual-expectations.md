---
layout: post
title: "Object detection can be improved using human-derived contextual expectations"
date: 2017-10-15 06:33:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Harish Katti, Marius V. Peelen, S. P. Arun
mathjax: true
---

* content
{:toc}

##### Abstract
Each object in the world occurs in a specific context: cars are seen on highways but not in forests. Contextual information is generally thought to facilitate computation by constraining locations to search. But can knowing context yield tangible benefits in object detection? For it to do so, scene context needs to be learned independently from target features. However this is impossible in traditional object detection where classifiers are trained on images containing both target features and surrounding coarse scene features. In contrast, we humans have the opportunity to learn context and target features separately, such as when we see highways without cars. Here we show for the first time that human-derived scene expectations can be used to improve object detection performance in machines. To measure these expectations, we asked human subjects to indicate the scale, location and likelihood at which targets may occur on scenes containing no targets. Humans showed highly systematic expectations that we could accurately predict using scene features. We then augmented state-of-the-art object detectors (based on deep neural networks) with these human-derived expectations on novel scenes to produce a significant (1-3%) improvement in detecting cars and people in scenes. This improvement was due to low-confidence detector matches being correctly relabeled as targets when they occurred in likely scenes.

##### Abstract (translated by Google)
世界上的每一个物体都是在一个特定的背景下出现的：在高速公路上看到汽车，而在森林里则看不见通常认为上下文信息通过约束要搜索的位置来促进计算。但是，能否了解上下文在对象检测中产生实际的好处？为此，场景上下文需要独立于目标特征来学习。然而，在传统的对象检测中这是不可能的，其中分类器在包含目标特征和周围粗糙场景特征的图像上训练。相比之下，我们人类有机会分别学习背景和目标特征，例如当我们看到没有汽车的高速公路时。在这里，我们首次展示了人类派生的场景期望可以用来改善机器中的物体检测性能。为了衡量这些期望，我们要求人类科目指出在不包含目标的场景中可能出现的尺度，位置和可能性。人类表现出非常系统的期望，我们可以准确预测使用场景特征。然后，我们在新的场景中增加了最新的物体探测器（基于深度神经网络）和这些人为的期望值，从而在检测场景中的汽车和人物时产生显着的（1-3％）改善。这种改进是由于低可信度检测器匹配在可能的场景中被正确地重新标记为目标。

##### URL
[https://arxiv.org/abs/1611.07218](https://arxiv.org/abs/1611.07218)

##### PDF
[https://arxiv.org/pdf/1611.07218](https://arxiv.org/pdf/1611.07218)

