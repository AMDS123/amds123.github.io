---
layout: post
title: "Detecting Oriented Text in Natural Images by Linking Segments"
date: 2017-04-13 17:40:43
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Baoguang Shi, Xiang Bai, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Most state-of-the-art text detection methods are specific to horizontal Latin text and are not fast enough for real-time applications. We introduce Segment Linking (SegLink), an oriented text detection method. The main idea is to decompose text into two locally detectable elements, namely segments and links. A segment is an oriented box covering a part of a word or text line; A link connects two adjacent segments, indicating that they belong to the same word or text line. Both elements are detected densely at multiple scales by an end-to-end trained, fully-convolutional neural network. Final detections are produced by combining segments connected by links. Compared with previous methods, SegLink improves along the dimensions of accuracy, speed, and ease of training. It achieves an f-measure of 75.0% on the standard ICDAR 2015 Incidental (Challenge 4) benchmark, outperforming the previous best by a large margin. It runs at over 20 FPS on 512x512 images. Moreover, without modification, SegLink is able to detect long lines of non-Latin text, such as Chinese.

##### Abstract (translated by Google)
大多数最先进的文本检测方法是特定于水平拉丁文本的，对于实时应用程序来说速度不够快。我们引入段链接（SegLink），一种面向文本的检测方法。主要思想是将文本分解为两个本地可检测的元素，即段和链接。段是覆盖单词或文本行的一部分的定向框;链接连接两个相邻的段，表示它们属于同一个单词或文本行。通过端到端训练的全卷积神经网络在多个尺度上密集地检测这两个元素。最后的检测是通过链接链接来组合生成的。与以前的方法相比，SegLink在精度，速度和易于训练方面都有所提高。它在标准的ICDAR 2015附加（挑战4）基准测试中获得了75.0％的f-measure，大幅超越了以前的最好成绩。它在512x512图像上运行速度超过20 FPS。此外，SegLink无需修改，即可检测长长的非拉丁文文本，如中文。

##### URL
[https://arxiv.org/abs/1703.06520](https://arxiv.org/abs/1703.06520)

##### PDF
[https://arxiv.org/pdf/1703.06520](https://arxiv.org/pdf/1703.06520)

