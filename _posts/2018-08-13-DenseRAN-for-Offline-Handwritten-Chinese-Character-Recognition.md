---
layout: post
title: "DenseRAN for Offline Handwritten Chinese Character Recognition"
date: 2018-08-13 10:16:08
categories: arXiv_CV
tags: arXiv_CV Attention Caption RNN Deep_Learning Recognition
author: Wenchao Wang, Jianshu Zhang, Jun Du, Zi-Rui Wang, Yixing Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, great success has been achieved in offline handwritten Chinese character recognition by using deep learning methods. Chinese characters are mainly logographic and consist of basic radicals, however, previous research mostly treated each Chinese character as a whole without explicitly considering its internal two-dimensional structure and radicals. In this study, we propose a novel radical analysis network with densely connected architecture (DenseRAN) to analyze Chinese character radicals and its two-dimensional structures simultaneously. DenseRAN first encodes input image to high-level visual features by employing DenseNet as an encoder. Then a decoder based on recurrent neural networks is employed, aiming at generating captions of Chinese characters by detecting radicals and two-dimensional structures through attention mechanism. The manner of treating a Chinese character as a composition of two-dimensional structures and radicals can reduce the size of vocabulary and enable DenseRAN to possess the capability of recognizing unseen Chinese character classes, only if the corresponding radicals have been seen in training set. Evaluated on ICDAR-2013 competition database, the proposed approach significantly outperforms whole-character modeling approach with a relative character error rate (CER) reduction of 18.54%. Meanwhile, for the case of recognizing 3277 unseen Chinese characters in CASIA-HWDB1.2 database, DenseRAN can achieve a character accuracy of about 41% while the traditional whole-character method has no capability to handle them.

##### Abstract (translated by Google)
最近，通过深度学习方法在离线手写汉字识别方面取得了巨大成功。汉字主要是语标，由基本的自由基组成，然而，以往的研究大多将每个汉字作为一个整体对待，而没有明确考虑其内部的二维结构和自由基。在这项研究中，我们提出了一个新的激进分析网络与密集连接架构（DenseRAN）同时分析汉字自由基及其二维结构。 DenseRAN首先通过使用DenseNet作为编码器将输入图像编码为高级视觉特征。然后采用基于递归神经网络的解码器，旨在通过注意机制检测自由基和二维结构来生成汉字字幕。将汉字作为二维结构和部首的组合处理的方式可以减小词汇的大小，并且只有在训练集中看到相应的部首才能使DenseRAN具有识别看不见的汉字类的能力。通过对ICDAR-2013竞争数据库的评估，该方法明显优于全字符建模方法，相对字符错误率（CER）降低18.54％。同时，对于在CASIA-HWDB1.2数据库中识别3277个看不见的汉字的情况，DenseRAN可以达到约41％的字符精度，而传统的全字符方法无法处理它们。

##### URL
[http://arxiv.org/abs/1808.04134](http://arxiv.org/abs/1808.04134)

##### PDF
[http://arxiv.org/pdf/1808.04134](http://arxiv.org/pdf/1808.04134)

