---
layout: post
title: "Word Searching in Scene Image and Video Frame in Multi-Script Scenario using Dynamic Shape Coding"
date: 2017-08-30 16:45:52
categories: arXiv_CV
tags: arXiv_CV OCR Recognition
author: Partha Pratim Roy, Ayan Kumar Bhunia, Avirup Bhattacharyya, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Retrieval of text information from natural scene images and video frames is a challenging task due to its inherent problems like complex character shapes, low resolution, background noise, etc. Available OCR systems often fail to retrieve such information in scene/video frames. Keyword spotting, an alternative way to retrieve information, performs efficient text searching in such scenarios. However, current word spotting techniques in scene/video images are script-specific and they are mainly developed for Latin script. This paper presents a novel word spotting framework using dynamic shape coding for text retrieval in natural scene image and video frames. The framework is designed to search query keyword from multiple scripts with the help of on-the-fly script-wise keyword generation for the corresponding script. We have used a two-stage word spotting approach using Hidden Markov Model (HMM) to detect the translated keyword in a given text line by identifying the script of the line. A novel unsupervised dynamic shape coding based scheme has been used to group similar shape characters to avoid confusion and to improve text alignment. Next, the hypotheses locations are verified to improve retrieval performance. To evaluate the proposed system for searching keyword from natural scene image and video frames, we have considered two popular Indic scripts such as Bangla (Bengali) and Devanagari along with English. Inspired by the zone-wise recognition approach in Indic scripts[1], zone-wise text information has been used to improve the traditional word spotting performance in Indic scripts. For our experiment, a dataset consisting of images of different scenes and video frames of English, Bangla and Devanagari scripts were considered. The results obtained showed the effectiveness of our proposed word spotting approach.

##### Abstract (translated by Google)
从自然场景图像和视频帧中检索文本信息是一个具有挑战性的任务，由于其固有的问题，如复杂的字符形状，低分辨率，背景噪声等。可用的OCR系统通常无法在场景/视频帧中检索这样的信息。关键字识别是一种检索信息的替代方法，可在这种情况下执行高效的文本搜索。然而，现场/视频图像中的当前单词识别技术是脚本特定的，并且它们主要是为拉丁脚本而开发的。本文提出了一种利用动态形状编码在自然场景图像和视频帧中进行文本检索的新词检测框架。该框架旨在通过为相应脚本实时生成脚本智能关键字来从多个脚本中搜索查询关键字。我们已经使用了一个使用隐马尔可夫模型（HMM）的两阶段单词识别方法，通过识别该行的脚本来检测给定文本行中的翻译关键字。一种新型的无监督动态形状编码的方案已经被用来对相似的形状字符进行分组以避免混淆并改善文本对齐。接下来，验证假设位置以改善检索性能。为了评估从自然场景图像和视频帧中搜索关键词的系统，我们考虑了孟加拉（Bangla）和梵文（Devanagari）这两种流行的印度语脚本以及英语。受到印度文字[1]中的区域识别方法的启发，区域文本信息已被用于改进印度文字中传统的字词识别性能。在我们的实验中，我们考虑了由英语，孟加拉语和梵文脚本的不同场景和视频帧的图像组成的数据集。所获得的结果显示了我们提出的字词识别方法的有效性。

##### URL
[https://arxiv.org/abs/1708.05529](https://arxiv.org/abs/1708.05529)

##### PDF
[https://arxiv.org/pdf/1708.05529](https://arxiv.org/pdf/1708.05529)

