---
layout: post
title: "Improving OCR Accuracy on Early Printed Books using Deep Convolutional Networks"
date: 2018-02-27 17:17:50
categories: arXiv_CV
tags: arXiv_CV OCR CNN RNN Prediction
author: Christoph Wick, Christian Reul, Frank Puppe
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a combination of a convolutional and a LSTM network to improve the accuracy of OCR on early printed books. While the standard model of line based OCR uses a single LSTM layer, we utilize a CNN- and Pooling-Layer combination in advance of an LSTM layer. Due to the higher amount of trainable parameters the performance of the network relies on a high amount of training examples to unleash its power. Hereby, the error is reduced by a factor of up to 44%, yielding a CER of 1% and below. To further improve the results we use a voting mechanism to achieve character error rates (CER) below $0.5%$. The runtime of the deep model for training and prediction of a book behaves very similar to a shallow network.

##### Abstract (translated by Google)
本文提出了卷积和LSTM网络的组合，以提高早期印刷书籍的OCR准确性。虽然基于行的OCR的标准模型使用单个LSTM层，但我们在LSTM层之前使用了CNN和Pooling-Layer组合。由于可训练参数的数量较多，网络的性能依赖于大量的训练样例来释放其力量。因此，误差减少高达44％，产生1％及以下的CER。为了进一步改进结果，我们使用投票机制来实现低于$ 0.5％$的字符错误率（CER）。用于训练和预测书籍的深层模型的运行时间表现与浅层网络非常相似。

##### URL
[https://arxiv.org/abs/1802.10033](https://arxiv.org/abs/1802.10033)

##### PDF
[https://arxiv.org/pdf/1802.10033](https://arxiv.org/pdf/1802.10033)

