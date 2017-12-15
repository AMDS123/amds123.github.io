---
layout: post
title: "Very Deep Convolutional Neural Networks for Robust Speech Recognition"
date: 2016-10-02 13:29:14
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Optimization RNN Recognition
author: Yanmin Qian, Philip C Woodland
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes the extension and optimization of our previous work on very deep convolutional neural networks (CNNs) for effective recognition of noisy speech in the Aurora 4 task. The appropriate number of convolutional layers, the sizes of the filters, pooling operations and input feature maps are all modified: the filter and pooling sizes are reduced and dimensions of input feature maps are extended to allow adding more convolutional layers. Furthermore appropriate input padding and input feature map selection strategies are developed. In addition, an adaptation framework using joint training of very deep CNN with auxiliary features i-vector and fMLLR features is developed. These modifications give substantial word error rate reductions over the standard CNN used as baseline. Finally the very deep CNN is combined with an LSTM-RNN acoustic model and it is shown that state-level weighted log likelihood score combination in a joint acoustic model decoding scheme is very effective. On the Aurora 4 task, the very deep CNN achieves a WER of 8.81%, further 7.99% with auxiliary feature joint training, and 7.09% with LSTM-RNN joint decoding.

##### Abstract (translated by Google)
本文描述了我们以前在非常深的卷积神经网络（CNN）上进行扩展和优化，以有效识别Aurora 4任务中的噪声语音。合适数量的卷积图层，过滤器的尺寸，合并操作和输入特征图都被修改：滤波器和合并尺寸被减小，并且输入特征图的尺寸被扩展以允许添加更多的卷积层。此外，开发适当的输入填充和输入特征图选择策略。此外，还开发了一个使用非常深的CNN与辅助特征i-vector和fMLLR特征的联合训练的自适应框架。这些修改提供了相对于用作基线的标准CNN的实际的字错误率降低。最后将非常深的CNN与LSTM-RNN声学模型相结合，表明联合声学模型解码方案中的状态级加权对数似然分值组合是非常有效的。在Aurora 4任务中，CNN深度达到8.81％，辅助特征联合训练达到7.99％，LSTM-RNN联合解码达到7.09％。

##### URL
[https://arxiv.org/abs/1610.00277](https://arxiv.org/abs/1610.00277)

##### PDF
[https://arxiv.org/pdf/1610.00277](https://arxiv.org/pdf/1610.00277)

