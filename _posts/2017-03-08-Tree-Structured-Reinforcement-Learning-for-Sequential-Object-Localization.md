---
layout: post
title: "Tree-Structured Reinforcement Learning for Sequential Object Localization"
date: 2017-03-08 05:24:52
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Zequn Jie, Xiaodan Liang, Jiashi Feng, Xiaojie Jin, Wen Feng Lu, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Existing object proposal algorithms usually search for possible object regions over multiple locations and scales separately, which ignore the interdependency among different objects and deviate from the human perception procedure. To incorporate global interdependency between objects into object localization, we propose an effective Tree-structured Reinforcement Learning (Tree-RL) approach to sequentially search for objects by fully exploiting both the current observation and historical search paths. The Tree-RL approach learns multiple searching policies through maximizing the long-term reward that reflects localization accuracies over all the objects. Starting with taking the entire image as a proposal, the Tree-RL approach allows the agent to sequentially discover multiple objects via a tree-structured traversing scheme. Allowing multiple near-optimal policies, Tree-RL offers more diversity in search paths and is able to find multiple objects with a single feed-forward pass. Therefore, Tree-RL can better cover different objects with various scales which is quite appealing in the context of object proposal. Experiments on PASCAL VOC 2007 and 2012 validate the effectiveness of the Tree-RL, which can achieve comparable recalls with current object proposal algorithms via much fewer candidate windows.

##### Abstract (translated by Google)
现有的对象提议算法通常在多个位置搜索可能的对象区域，并且分别缩放，忽略不同对象之间的相互依赖性，偏离人类的感知过程。为了将对象之间的全局相互依赖性融入到对象本地化中，我们提出了一种有效的树形结构强化学习（Tree-RL）方法，通过充分利用当前的观察和历史搜索路径来依次搜索对象。 Tree-RL方法通过最大化反映所有对象的定位精度的长期奖励来学习多个搜索策略。从将整个图像作为建议开始，Tree-RL方法允许代理通过树形结构遍历方案顺序发现多个对象。允许多个接近最佳的策略，Tree-RL在搜索路径中提供更多的多样性，并且能够通过单个前馈传递找到多个对象。因此，Tree-RL可以更好地覆盖不同尺度的物体，这在对象建议的背景下是非常有吸引力的。对PASCAL VOC 2007和2012的实验验证了Tree-RL的有效性，它可以通过少得多的候选窗口实现与当前对象提议算法类似的召回。

##### URL
[https://arxiv.org/abs/1703.02710](https://arxiv.org/abs/1703.02710)

##### PDF
[https://arxiv.org/pdf/1703.02710](https://arxiv.org/pdf/1703.02710)

