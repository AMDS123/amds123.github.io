---
layout: post
title: "DeepCache: Principled Cache for Mobile Deep Vision"
date: 2018-08-28 15:13:47
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: Mengwei Xu, Mengze Zhu, Yunxin Liu, Felix Xiaozhu Lin, Xuanzhe Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present DeepCache, a principled cache design for deep learning inference in continuous mobile vision. DeepCache benefits model execution efficiency by exploiting temporal locality in input video streams. It addresses a key challenge raised by mobile vision: the cache must operate under video scene variation, while trading off among cacheability, overhead, and loss in model accuracy. At the input of a model, DeepCache discovers video temporal locality by exploiting the video's internal structure, for which it borrows proven heuristics from video compression; into the model, DeepCache propagates regions of reusable results by exploiting the model's internal structure. Notably, DeepCache eschews applying video heuristics to model internals which are not pixels but high-dimensional, difficult-to-interpret data. Our implementation of DeepCache works with unmodified deep learning models, requires zero developer's manual effort, and is therefore immediately deployable on off-the-shelf mobile devices. Our experiments show that DeepCache saves inference execution time by 18% on average and up to 47%. DeepCache reduces system energy consumption by 20% on average.

##### Abstract (translated by Google)
我们介绍了DeepCache，这是一种原理缓存设计，用于连续移动视觉中的深度学习推理。 DeepCache通过利用输入视频流中的时间局部性来提高模型执行效率。它解决了移动视觉带来的一个关键挑战：缓存必须在视频场景变化下运行，同时在可缓存性，开销和模型精度损失之间进行权衡。在模型的输入处，DeepCache通过利用视频的内部结构来发现视频时间局部性，为此借鉴了视频压缩的经过验证的启发式算法;在模型中，DeepCache通过利用模型的内部结构来传播可重用结果的区域。值得注意的是，DeepCache避免将视频启发式应用于模型内部结构，该内部结构不是像素，而是高维，难以理解的数据。我们的DeepCache实现与未修改的深度学习模型一起使用，需要零开发人员的手动工作，因此可立即部署在现成的移动设备上。我们的实验表明，DeepCache平均将推理执行时间节省了18％，最多可节省47％。 DeepCache平均将系统能耗降低20％。

##### URL
[http://arxiv.org/abs/1712.01670](http://arxiv.org/abs/1712.01670)

##### PDF
[http://arxiv.org/pdf/1712.01670](http://arxiv.org/pdf/1712.01670)

