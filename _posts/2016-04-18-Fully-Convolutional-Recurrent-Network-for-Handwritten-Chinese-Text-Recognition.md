---
layout: post
title: "Fully Convolutional Recurrent Network for Handwritten Chinese Text Recognition"
date: 2016-04-18 01:28:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Language_Model Prediction Recognition
author: Zecheng Xie, Zenghui Sun, Lianwen Jin, Ziyong Feng, Shuye Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an end-to-end framework, namely fully convolutional recurrent network (FCRN) for handwritten Chinese text recognition (HCTR). Unlike traditional methods that rely heavily on segmentation, our FCRN is trained with online text data directly and learns to associate the pen-tip trajectory with a sequence of characters. FCRN consists of four parts: a path-signature layer to extract signature features from the input pen-tip trajectory, a fully convolutional network to learn informative representation, a sequence modeling layer to make per-frame predictions on the input sequence and a transcription layer to translate the predictions into a label sequence. The FCRN is end-to-end trainable in contrast to conventional methods whose components are separately trained and tuned. We also present a refined beam search method that efficiently integrates the language model to decode the FCRN and significantly improve the recognition results. We evaluate the performance of the proposed method on the test sets from the databases CASIA-OLHWDB and ICDAR 2013 Chinese handwriting recognition competition, and both achieve state-of-the-art performance with correct rates of 96.40% and 95.00%, respectively.

##### Abstract (translated by Google)
本文提出了一个端到端的框架，即完全卷积递归网络（FCRN）手写中文文本识别（HCTR）。与严重依赖分割的传统方法不同，我们的FCRN直接使用在线文本数据进行训练，并学习将笔尖轨迹与一系列字符相关联。 FCRN由四部分组成：从输入笔尖轨迹中提取签名特征的路径签名层，学习信息表示的完全卷积网络，对输入序列进行每帧预测的序列建模层和转录层将预测翻译成标签序列。 FCRN是端到端可训练的，而传统方法的组成部分是分别训练和调整的。我们还提出了一种精确的波束搜索方法，有效地整合语言模型来解码FCRN，并显着改善识别结果。我们通过数据库CASIA-OLHWDB和ICDAR 2013中文手写识别竞赛，对测试集上的方法性能进行了评估，分别达到了96.40％和95.00％的正确率。

##### URL
[https://arxiv.org/abs/1604.04953](https://arxiv.org/abs/1604.04953)

##### PDF
[https://arxiv.org/pdf/1604.04953](https://arxiv.org/pdf/1604.04953)

