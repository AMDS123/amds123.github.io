---
layout: post
title: "Learning Video Summarization Using Unpaired Data"
date: 2018-05-30 18:48:25
categories: arXiv_CV
tags: arXiv_CV Summarization
author: Mrigank Rochan, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of video summarization. Given an input raw video, the goal is to select a small subset of key frames from the input video to create a shorter summary video that best describes the content of the original video. Most of the current state-of-the-art video summarization approaches use supervised learning and require training data in the form of paired videos. Each pair consists of a raw input video and a ground-truth summary video curated by human annotators. However, it is difficult to create such paired training data. To address this limitation, we propose a novel formulation to learn video summarization from unpaired data. Our method only requires training data in the form of two sets of videos: a set of raw videos ($V$) and another set of summary videos ($S$). We do not require the correspondence between these two sets of videos. We argue that this type of data is much easier to collect. We present an approach that learns to generate summary videos from such unpaired data. We achieve this by learning a mapping function $F : V \rightarrow S $ which tries to make the distribution of generated summary videos from $F(V)$ similar to the distribution of $S$ while enforcing a high visual diversity constraint on $F(V)$. Experimental results on two benchmark datasets show that our proposed approach significantly outperforms other alternative methods.

##### Abstract (translated by Google)
我们考虑视频摘要的问题。给定一个原始视频输入，其目标是从输入视频中选择一小部分关键帧来创建一个能够最好地描述原始视频内容的简短摘要视频。目前最先进的视频摘要方法大多使用监督式学习，并需要配对视频形式的培训数据。每一对由原始输入视频和由人类注释者策划的地面实况摘要视频组成。但是，创建这样的配对训练数据很困难。为了解决这个限制，我们提出了一种新的公式来学习不成对数据的视频摘要。我们的方法只需要两组视频的训练数据：一组原始视频（$ V $）和另一组摘要视频（$ S $）。我们不需要这两组视频之间的对应关系。我们认为这种类型的数据更容易收集。我们提供了一种方法，学习如何从这些不成对的数据中生成摘要视频。我们通过学习映射函数$ F：V \ rightarrow S $来实现这一点，该映射函数试图使生成的摘要视频的分布从$ F（V）$类似于$ S $的分布，同时对$执行高视觉多样性约束F（V）$。两个基准数据集的实验结果表明，我们提出的方法明显优于其他替代方法。

##### URL
[http://arxiv.org/abs/1805.12174](http://arxiv.org/abs/1805.12174)

##### PDF
[http://arxiv.org/pdf/1805.12174](http://arxiv.org/pdf/1805.12174)

