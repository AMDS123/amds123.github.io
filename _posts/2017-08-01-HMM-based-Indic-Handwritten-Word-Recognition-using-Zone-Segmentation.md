---
layout: post
title: "HMM-based Indic Handwritten Word Recognition using Zone Segmentation"
date: 2017-08-01 09:52:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Partha Pratim Roy, Ayan Kumar Bhunia, Ayan Das, Prasenjit Dey, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach towards Indic handwritten word recognition using zone-wise information. Because of complex nature due to compound characters, modifiers, overlapping and touching, etc., character segmentation and recognition is a tedious job in Indic scripts (e.g. Devanagari, Bangla, Gurumukhi, and other similar scripts). To avoid character segmentation in such scripts, HMM-based sequence modeling has been used earlier in holistic way. This paper proposes an efficient word recognition framework by segmenting the handwritten word images horizontally into three zones (upper, middle and lower) and recognize the corresponding zones. The main aim of this zone segmentation approach is to reduce the number of distinct component classes compared to the total number of classes in Indic scripts. As a result, use of this zone segmentation approach enhances the recognition performance of the system. The components in middle zone where characters are mostly touching are recognized using HMM. After the recognition of middle zone, HMM based Viterbi forced alignment is applied to mark the left and right boundaries of the characters. Next, the residue components, if any, in upper and lower zones in their respective boundary are combined to achieve the final word level recognition. Water reservoir feature has been integrated in this framework to improve the zone segmentation and character alignment defects while segmentation. A novel sliding window-based feature, called Pyramid Histogram of Oriented Gradient (PHOG) is proposed for middle zone recognition. An exhaustive experiment is performed on two Indic scripts namely, Bangla and Devanagari for the performance evaluation. From the experiment, it has been noted that proposed zone-wise recognition improves accuracy with respect to the traditional way of Indic word recognition.

##### Abstract (translated by Google)
本文提出了一种新颖的方法对印度手写字识别使用区域明智的信息。由于复合字符，修饰符，重叠和触摸等复杂性质，字符分割和识别在印度语脚本（例如梵文，孟加拉语，古鲁穆希和其他类似脚本）中是一项繁琐的工作。为了避免在这样的脚本中进行字符分割，基于HMM的序列建模早已被整体使用。本文提出了一种高效的单词识别框架，将手写单词图像水平分割成三个区域（上，中，下），并识别相应的区域。这种区域分割方法的主要目的是减少与印度语脚本中类别总数相比不同组件类别的数量。结果，使用这种区域分割方法增强了系统的识别性能。使用HMM识别字符大部分触摸的中间区域的组件。识别中间区域后，应用基于HMM的Viterbi强制对齐方式标记字符的左右边界。接下来，如果有的话，在其各自边界的上部和下部区域中的残余成分被组合以实现最终的词级识别。水库功能已经集成在这个框架中，以改善分割时的区域分割和字符对齐缺陷。提出了一种基于滑动窗口特征的金字塔方向梯度直方图（PHOG）用于中间区域识别。对印度尼西亚和印度尼西亚两个印度文字版本进行了详尽的实验，以进行绩效评估。从实验中，已经注意到，提出的区域方式识别相对于传统的印度文字识别方式提高了准确性。

##### URL
[https://arxiv.org/abs/1708.00227](https://arxiv.org/abs/1708.00227)

##### PDF
[https://arxiv.org/pdf/1708.00227](https://arxiv.org/pdf/1708.00227)

