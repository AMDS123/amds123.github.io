---
layout: post
title: "From Thumbnails to Summaries - A single Deep Neural Network to Rule Them All"
date: 2018-08-01 06:24:39
categories: arXiv_CV
tags: arXiv_CV Sparse RNN
author: Hongxiang Gu, Viswanathan Swaminathan
mathjax: true
---

* content
{:toc}

##### Abstract
Video summaries come in many forms, from traditional single-image thumbnails, animated thumbnails, storyboards, to trailer-like video summaries. Content creators use the summaries to display the most attractive portion of their videos; the users use them to quickly evaluate if a video is worth watching. All forms of summaries are essential to video viewers, content creators, and advertisers. Often video content management systems have to generate multiple versions of summaries that vary in duration and presentational forms. We present a framework ReconstSum that utilizes LSTM-based autoencoder architecture to extract and select a sparse subset of video frames or keyshots that optimally represent the input video in an unsupervised manner. The encoder selects a subset from the input video while the decoder seeks to reconstruct the video from the selection. The goal is to minimize the difference between the original input video and the reconstructed video. Our method is easily extendable to generate a variety of applications including static video thumbnails, animated thumbnails, storyboards and "trailer-like" highlights. We specifically study and evaluate two most popular use cases: thumbnail generation and storyboard generation. We demonstrate that our methods generate better results than the state-of-the-art techniques in both use cases.

##### Abstract (translated by Google)
视频摘要有多种形式，从传统的单图像缩略图，动画缩略图，故事板到预告片视频摘要。内容创建者使用摘要显示其视频中最具吸引力的部分;用户使用它们来快速评估视频是否值得观看。所有形式的摘要对视频观看者，内容创建者和广告商都至关重要。视频内容管理系统通常必须生成多个版本的摘要，这些摘要的持续时间和表现形式各不相同。我们提出了一个框架ReconstSum，它利用基于LSTM的自动编码器架构来提取和选择以无人监督的方式最佳地表示输入视频的视频帧或按键的稀疏子集。当解码器试图从选择中重建视频时，编码器从输入视频中选择子集。目标是最小化原始输入视频和重建视频之间的差异。我们的方法可以轻松扩展，以生成各种应用程序，包括静态视频缩略图，动画缩略图，故事板和“预告片”亮点。我们专门研究和评估两个最常用的用例：缩略图生成和故事板生成。我们证明了我们的方法比两种用例中的最先进技术产生更好的结果。

##### URL
[http://arxiv.org/abs/1808.00184](http://arxiv.org/abs/1808.00184)

##### PDF
[http://arxiv.org/pdf/1808.00184](http://arxiv.org/pdf/1808.00184)

