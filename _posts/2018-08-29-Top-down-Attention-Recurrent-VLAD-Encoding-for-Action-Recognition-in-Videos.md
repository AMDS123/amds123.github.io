---
layout: post
title: "Top-down Attention Recurrent VLAD Encoding for Action Recognition in Videos"
date: 2018-08-29 15:41:36
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition Image_Classification Classification Recognition
author: Swathikiran Sudhakaran, Oswald Lanz
mathjax: true
---

* content
{:toc}

##### Abstract
Most recent approaches for action recognition from video leverage deep architectures to encode the video clip into a fixed length representation vector that is then used for classification. For this to be successful, the network must be capable of suppressing irrelevant scene background and extract the representation from the most discriminative part of the video. Our contribution builds on the observation that spatio-temporal patterns characterizing actions in videos are highly correlated with objects and their location in the video. We propose Top-down Attention Action VLAD (TA-VLAD), a deep recurrent architecture with built-in spatial attention that performs temporally aggregated VLAD encoding for action recognition from videos. We adopt a top-down approach of attention, by using class specific activation maps obtained from a deep CNN pre-trained for image classification, to weight appearance features before encoding them into a fixed-length video descriptor using Gated Recurrent Units. Our method achieves state of the art recognition accuracy on HMDB51 and UCF101 benchmarks.

##### Abstract (translated by Google)
最近的视频动作识别方法利用深层体系结构将视频片段编码为固定长度的表示向量，然后用于分类。为了使其成功，网络必须能够抑制不相关的场景背景并从视频的最具辨别力的部分中提取表示。我们的贡献建立在以下观察的基础上：视频中表征动作的时空模式与对象及其在视频中的位置高度相关。我们提出了自上而下注意力行动VLAD（TA-VLAD），这是一种具有内置空间关注度的深度复现架构，可执行时间聚合的VLAD编码，以便从视频中识别动作。我们采用自上而下的关注方法，通过使用从预先训练用于图像分类的深度CNN获得的类特定激活图，在使用门控递归单元将它们编码成固定长度视频描述符之前加权外观特征。我们的方法在HMDB51和UCF101基准测试上实现了最先进的识别精度。

##### URL
[http://arxiv.org/abs/1808.09892](http://arxiv.org/abs/1808.09892)

##### PDF
[http://arxiv.org/pdf/1808.09892](http://arxiv.org/pdf/1808.09892)

