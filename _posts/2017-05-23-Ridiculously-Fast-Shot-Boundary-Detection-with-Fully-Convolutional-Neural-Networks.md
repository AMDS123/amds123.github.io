---
layout: post
title: "Ridiculously Fast Shot Boundary Detection with Fully Convolutional Neural Networks"
date: 2017-05-23 12:39:51
categories: arXiv_CV
tags: arXiv_CV Video_Indexing Summarization Action_Recognition CNN Detection Recognition
author: Michael Gygli
mathjax: true
---

* content
{:toc}

##### Abstract
Shot boundary detection (SBD) is an important component of many video analysis tasks, such as action recognition, video indexing, summarization and editing. Previous work typically used a combination of low-level features like color histograms, in conjunction with simple models such as SVMs. Instead, we propose to learn shot detection end-to-end, from pixels to final shot boundaries. For training such a model, we rely on our insight that all shot boundaries are generated. Thus, we create a dataset with one million frames and automatically generated transitions such as cuts, dissolves and fades. In order to efficiently analyze hours of videos, we propose a Convolutional Neural Network (CNN) which is fully convolutional in time, thus allowing to use a large temporal context without the need to repeatedly processing frames. With this architecture our method obtains state-of-the-art results while running at an unprecedented speed of more than 120x real-time.

##### Abstract (translated by Google)
镜头边界检测（SBD）是许多视频分析任务的重要组成部分，如动作识别，视频索引，汇总和编辑。以前的工作通常使用像颜色直方图这样的低级特征的组合，以及诸如SVM之类的简单模型。相反，我们建议学习端到端的镜头检测，从像素到最终的镜头边界。为了训练这样一个模型，我们依靠我们的洞察力来产生所有的镜头边界。因此，我们创建一个具有一百万帧的数据集，并自动生成切换，分解和淡入等转换。为了有效地分析视频小时，我们提出了一个完全卷积的卷积神经网络（CNN），因此允许使用大的时间上下文，而不需要重复处理帧。采用这种架构，我们的方法以前所未有的超过120倍的实时速度运行，获得了最先进的结果。

##### URL
[https://arxiv.org/abs/1705.08214](https://arxiv.org/abs/1705.08214)

##### PDF
[https://arxiv.org/pdf/1705.08214](https://arxiv.org/pdf/1705.08214)

