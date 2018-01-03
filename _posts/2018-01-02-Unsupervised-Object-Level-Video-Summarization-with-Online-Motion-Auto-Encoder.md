---
layout: post
title: "Unsupervised Object-Level Video Summarization with Online Motion Auto-Encoder"
date: 2018-01-02 03:55:36
categories: arXiv_CV
tags: arXiv_CV Summarization Optimization
author: Yujia Zhang, Xiaodan Liang, Dingwen Zhang, Min Tan, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised video summarization plays an important role on digesting, browsing, and searching the ever-growing videos everyday. Despite the great progress achieved by prior works (e.g., the frame-level video summarization), the underlying fine-grained semantic and motion information (i.e., objects of interest and their key motions) in online videos has been barely touched, which is more essential and beneficial for many down-streaming tasks (e.g., object retrieval) in an intelligent system. In this paper, we investigate a pioneer research direction towards the fine-grained unsupervised object-level video summarization. It can be distinguished from existing pipelines in two aspects: extracting key motions of participated objects, and learning to summarize in an unsupervised and online manner that is more applicable for online growing videos. To achieve this goal, we propose a novel online motion Auto-Encoder (online motion-AE) framework that functions on the super-segmented object motion clips. The online motion-AE mimics the online dictionary learning for memorizing past states of object motions by continuously updating a tailored recurrent auto-encoder network. This online updating scheme enables the differentiable optimization of jointly online feature learning and dictionary learning to discriminate key object-motion clips. Finally, the key object-motion clips can be mined by using the reconstruction errors obtained by the online motion-AE. Comprehensive experiments on a newly-collected surveillance dataset and the public Base jumping, SumMe, and TVSum datasets have demonstrated the effectiveness of online motion-AE, and the application potential of fine-grained object-level video summarization.

##### Abstract (translated by Google)
无监督的视频摘要在日常消化，浏览和搜索不断增长的视频中发挥着重要的作用。尽管以前的作品（如帧级视频摘要）取得了很大的进展，但在线视频中的基础细粒度语义和运动信息（即感兴趣的对象及其关键动作）几乎没有被触及，对于智能系统中的许多下游流任务（例如，对象检索）是必不可少的和有益的。在本文中，我们研究了一个开创性的研究方向，即细粒度无监督对象级视频摘要。它可以从两个方面区别于现有的管道：提取参与对象的关键动作，学习以无监督和在线方式进行总结，更适用于在线成长视频。为了实现这个目标，我们提出了一个新颖的在线运动自动编码器（在线运动AE）的框架，功能的超分段对象运动剪辑。在线运动AE通过不断更新定制的循环自动编码器网络来模拟在线词典学习以记忆对象运动的过去状态。这种在线更新方案使联合在线特征学习和词典学习的可微分优化能够区分关键的对象运动剪辑。最后，通过使用在线运动AE获得的重构误差可以挖掘关键物体运动剪辑。在新收集的监测数据集和公共基站跳跃，SumMe和TVSum数据集上的综合实验已经证明了在线运动AE的有效性以及细粒度对象级视频摘要的应用潜力。

##### URL
[http://arxiv.org/abs/1801.00543](http://arxiv.org/abs/1801.00543)

##### PDF
[http://arxiv.org/pdf/1801.00543](http://arxiv.org/pdf/1801.00543)

