---
layout: post
title: "Hierarchical Multi Task Learning With CTC"
date: 2018-07-18 18:57:37
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Classification Language_Model Prediction Multi_Task Recognition
author: Ramon Sanabria, Florian Metze
mathjax: true
---

* content
{:toc}

##### Abstract
In Automatic Speech Recognition, it is still challenging to learn useful intermediate representations when using of high-level (or abstract) target units such as words. Character or phoneme based systems tend to outperform word based systems as long as thousands of hours of training data are being used. In this paper, we first show how hierarchical multi-task training can encourage the formation of useful intermediate representations. We achieve this by performing Connectionist Temporal Classification at different levels of the network with targets of different granularity. Our model thus performs predictions in multiple scales of granularity for the same input. On the standard 300h Switchboard training setup, our hierarchical multi-task architecture exhibits improvements over single-task architectures with the same number of parameters. Our model obtains 14.0% Word Error Rate on the Eval2000 Switchboard subset without any decoder or language model, outperforming the current state-of-the-art on acoustic-to-word models.

##### Abstract (translated by Google)
在自动语音识别中，当使用诸如单词的高级（或抽象）目标单元时，学习有用的中间表示仍然是具有挑战性的。只要使用数千小时的训练数据，基于字符或音素的系统往往优于基于单词的系统。在本文中，我们首先展示了分层多任务训练如何能够鼓励形成有用的中间表征。我们通过在具有不同粒度的目标的网络的不同级别执行连接主义时间分类来实现这一点。因此，我们的模型针对相同的输入执行多个粒度尺度的预测。在标准的300h Switchboard培训设置中，我们的分层多任务架构比具有相同参数数量的单任务架构有所改进。我们的模型在没有任何解码器或语言模型的情况下在Eval2000交换机子集上获得14.0％的字错误率，优于当前最先进的声学到单词模型。

##### URL
[https://arxiv.org/abs/1807.07104](https://arxiv.org/abs/1807.07104)

##### PDF
[https://arxiv.org/pdf/1807.07104](https://arxiv.org/pdf/1807.07104)

