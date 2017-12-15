---
layout: post
title: "Landmark-based consonant voicing detection on multilingual corpora"
date: 2016-11-10 22:11:16
categories: arXiv_CL
tags: arXiv_CL Object_Detection CNN Detection
author: Xiang Kong, Xuesong Yang, Mark Hasegawa-Johnson, Jeung-Yoon Choi, Stefanie Shattuck-Hufnagel
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tests the hypothesis that distinctive feature classifiers anchored at phonetic landmarks can be transferred cross-lingually without loss of accuracy. Three consonant voicing classifiers were developed: (1) manually selected acoustic features anchored at a phonetic landmark, (2) MFCCs (either averaged across the segment or anchored at the landmark), and(3) acoustic features computed using a convolutional neural network (CNN). All detectors are trained on English data (TIMIT),and tested on English, Turkish, and Spanish (performance measured using F1 and accuracy). Experiments demonstrate that manual features outperform all MFCC classifiers, while CNNfeatures outperform both. MFCC-based classifiers suffer an F1reduction of 16% absolute when generalized from English to other languages. Manual features suffer only a 5% F1 reduction,and CNN features actually perform better in Turkish and Span-ish than in the training language, demonstrating that features capable of representing long-term spectral dynamics (CNN and landmark-based features) are able to generalize cross-lingually with little or no loss of accuracy

##### Abstract (translated by Google)
本文测试了锚定在语音地标上的独特特征分类器可以在不损失准确性的情况下跨语言转移的假设。开发了三种辅音浊音分类器：（1）锚定在语音标志上的手动选择的声学特征;（2）MFCC（在节段上平均或锚定在地标上）;以及（3）使用卷积神经网络计算的声学特征CNN）。所有探测器都接受英语数据（TIMIT）培训，并使用英语，土耳其语和西班牙语进行测试（使用F1和准确性测量性能）。实验证明，手动特征优于所有MFCC分类器，而CNN特性优于两者。基于MFCC的分类器在从英语推广到其他语言时遭受绝对16％的精简。手动功能仅遭受5％的F1减少，而CNN功能在土耳其语和跨度上比在训练语言中表现得更好，表明能够表示长期光谱动态特征（CNN和基于地标的特征）的特征能够概括地说是跨语言的，精确度很低或没有损失

##### URL
[https://arxiv.org/abs/1611.03533](https://arxiv.org/abs/1611.03533)

##### PDF
[https://arxiv.org/pdf/1611.03533](https://arxiv.org/pdf/1611.03533)

