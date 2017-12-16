---
layout: post
title: "Handwritten digit string recognition by combination of residual network and RNN-CTC"
date: 2017-10-09 14:16:00
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Recognition
author: Hongjian Zhan, Qingqing Wang, Yue Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network (RNN) and connectionist temporal classification (CTC) have showed successes in many sequence labeling tasks with the strong ability of dealing with the problems where the alignment between the inputs and the target labels is unknown. Residual network is a new structure of convolutional neural network and works well in various computer vision tasks. In this paper, we take advantage of the architectures mentioned above to create a new network for handwritten digit string recognition. First we design a residual network to extract features from input images, then we employ a RNN to model the contextual information within feature sequences and predict recognition results. At the top of this network, a standard CTC is applied to calculate the loss and yield the final results. These three parts compose an end-to-end trainable network. The proposed new architecture achieves the highest performances on ORAND-CAR-A and ORAND-CAR-B with recognition rates 89.75% and 91.14%, respectively. In addition, the experiments on a generated captcha dataset which has much longer string length show the potential of the proposed network to handle long strings.

##### Abstract (translated by Google)
递归神经网络（RNN）和连接主义时间分类（CTC）在许多序列标记任务中都取得了成功，具有很强的处理输入和目标标记之间的比对未知的问题的能力。残差网络是一种卷积神经网络的新结构，在各种计算机视觉任务中运行良好。在本文中，我们利用上述架构来创建一个新的手写数字串识别网络。首先设计一个残差网络从输入图像中提取特征，然后利用RNN对特征序列中的上下文信息进行建模并预测识别结果。在该网络的顶部，应用标准的CTC来计算损失并得出最终结果。这三个部分组成了一个端到端的可训练网络。所提出的新架构在ORAND-CAR-A和ORAND-CAR-B上达到最高的性能，识别率分别为89.75％和91.14％。另外，在生成的验证码数据集中具有更长的字符串长度的实验显示了所提出的网络处理长字符串的潜力。

##### URL
[https://arxiv.org/abs/1710.03112](https://arxiv.org/abs/1710.03112)

##### PDF
[https://arxiv.org/pdf/1710.03112](https://arxiv.org/pdf/1710.03112)

