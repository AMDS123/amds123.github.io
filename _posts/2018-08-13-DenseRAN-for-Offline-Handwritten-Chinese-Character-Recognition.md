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


##### URL
[https://arxiv.org/abs/1808.04134](https://arxiv.org/abs/1808.04134)

##### PDF
[https://arxiv.org/pdf/1808.04134](https://arxiv.org/pdf/1808.04134)

