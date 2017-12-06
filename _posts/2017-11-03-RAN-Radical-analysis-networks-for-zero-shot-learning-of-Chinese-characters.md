---
layout: post
title: 'RAN: Radical analysis networks for zero-shot learning of Chinese characters'
date: 2017-11-03 14:40:28
categories: arXiv_CV
tags: arXiv_CV Caption CNN RNN
author: Jianshu Zhang, Yixing Zhu, Jun Du, Lirong Dai
---

* content
{:toc}

##### Abstract
Chinese characters have a huge set of character categories, more than 20,000 and the number is still increasing as more and more novel characters continue being created. However, the enormous characters can be decomposed into a few fundamental structural radicals, only about 500. This paper introduces the Radical Analysis Networks (RAN) that recognize Chinese characters by identifying radicals and analyzing 2D spatial structures between them. The proposed RAN first extracts visual features from Chinese character input by employing convolutional neural networks as an encoder. Then a decoder based on recurrent neural networks is employed, who aims to generate a caption of Chinese character by detecting radicals and 2D structures through a spatial attention mechanism. The manner of treating Chinese character input as a composition of radicals rather than a single picture severely reduces the size of vocabulary and enables RAN to possess the ability of recognizing unseen Chinese character classes only if their radicals have been seen, called zero-shot learning. We test a simple implementation of RAN on experiments of recognizing printed Chinese characters with seen and unseen classes and RAN simultaneously obtains convincing performance on unseen classes and state-of-the-art performance on seen classes.

##### Abstract (translated by Google)
汉字有大量的人物类别，超过2万人，随着越来越多的小说人物的不断创作，人物数量还在不断增加。然而，巨大的字符可以分解成几个基本的结构性的自由基，只有大约500个。本文介绍了通过识别自由基并分析它们之间的二维空间结构来识别汉字的自由基分析网络（RAN）。提出的RAN首先采用卷积神经网络作为编码器，从汉字输入中提取视觉特征。然后采用基于递归神经网络的解码器，通过空间关注机制检测自由基和二维结构，生成汉字字幕。将汉字输入视为部首而不是单张照片的方式严重缩小了词汇量，使RAN只有在看到自己的激进分子时才具备识别看不见的汉字类的能力，称为零点学习。我们测试RAN的一个简单的实现，即用看不见的类识别印刷的汉字，RAN同时在看不见的类上获得令人信服的表现，并在所看到的类上获得最新的表现。

##### URL
[https://arxiv.org/abs/1711.01889](https://arxiv.org/abs/1711.01889)

