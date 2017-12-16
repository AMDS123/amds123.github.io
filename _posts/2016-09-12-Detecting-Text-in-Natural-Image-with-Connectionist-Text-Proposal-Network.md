---
layout: post
title: "Detecting Text in Natural Image with Connectionist Text Proposal Network"
date: 2016-09-12 21:12:46
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhi Tian, Weilin Huang, Tong He, Pan He, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel Connectionist Text Proposal Network (CTPN) that accurately localizes text lines in natural image. The CTPN detects a text line in a sequence of fine-scale text proposals directly in convolutional feature maps. We develop a vertical anchor mechanism that jointly predicts location and text/non-text score of each fixed-width proposal, considerably improving localization accuracy. The sequential proposals are naturally connected by a recurrent neural network, which is seamlessly incorporated into the convolutional network, resulting in an end-to-end trainable model. This allows the CTPN to explore rich context information of image, making it powerful to detect extremely ambiguous text. The CTPN works reliably on multi-scale and multi- language text without further post-processing, departing from previous bottom-up methods requiring multi-step post-processing. It achieves 0.88 and 0.61 F-measure on the ICDAR 2013 and 2015 benchmarks, surpass- ing recent results [8, 35] by a large margin. The CTPN is computationally efficient with 0:14s/image, by using the very deep VGG16 model [27]. Online demo is available at: this http URL

##### Abstract (translated by Google)
我们提出了一种新颖的连接文本提议网络（CTPN），它能够准确定位自然图像中的文本行。 CTPN直接在卷积特征图中检测一系列精细文本提议中的文本行。我们开发了一个垂直锚机制，联合预测每个固定宽度建议的位置和文本/非文本分数，大大提高了定位精度。顺序提案通过循环神经网络自然地连接起来，该网络无缝地结合到卷积网络中，从而形成端到端的可训练模型。这使得CTPN可以探索丰富的图像上下文信息，使其能够检测极其模糊的文本。 CTPN在多尺度和多语言的文本中可靠地工作，而不需要进一步的后处理，从以前的自底向上的方法需要多步骤后处理。它在ICDAR 2013和2015的基准上达到了0.88和0.61的F-measure，远远超过了最近的结果[8,35]。通过使用非常深的VGG16模型[27]，CTPN的计算效率为0：14s /图像。在线演示可在此http URL

##### URL
[https://arxiv.org/abs/1609.03605](https://arxiv.org/abs/1609.03605)

##### PDF
[https://arxiv.org/pdf/1609.03605](https://arxiv.org/pdf/1609.03605)

