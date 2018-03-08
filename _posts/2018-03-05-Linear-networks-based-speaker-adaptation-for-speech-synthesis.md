---
layout: post
title: "Linear networks based speaker adaptation for speech synthesis"
date: 2018-03-05 05:35:34
categories: arXiv_SD
tags: arXiv_SD
author: Zhiying Huang, Heng Lu, Ming Lei, Zhijie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Speaker adaptation methods aim to create fair quality synthesis speech voice font for target speakers while only limited resources available. Recently, as deep neural networks based statistical parametric speech synthesis (SPSS) methods become dominant in SPSS TTS back-end modeling, speaker adaptation under the neural network based SPSS framework has also became an important task. In this paper, linear networks (LN) is inserted in multiple neural network layers and fine-tuned together with output layer for best speaker adaptation performance. When adaptation data is extremely small, the low-rank plus diagonal(LRPD) decomposition for LN is employed to make the adapted voice more stable. Speaker adaptation experiments are conducted under a range of adaptation utterances numbers. Moreover, speaker adaptation from 1) female to female, 2) male to female and 3) female to male are investigated. Objective measurement and subjective tests show that LN with LRPD decomposition performs most stable when adaptation data is extremely limited, and our best speaker adaptation (SA) model with only 200 adaptation utterances achieves comparable quality with speaker dependent (SD) model trained with 1000 utterances, in both naturalness and similarity to target speaker.

##### Abstract (translated by Google)
演讲者适应方法旨在为目标演讲者创建质量合理的语音语音字体，同时只提供有限的资源。最近，随着基于深度神经网络的统计参数语音合成（SPSS）方法在SPSS TTS后端建模中占据主导地位，基于神经网络的SPSS框架下的说话人适应也成为一项重要任务。在本文中，线性网络（LN）插入多个神经网络层，并与输出层一起进行微调以获得最佳说话人适应性能。当适应数据非常小时，LN的低秩加对角线（LRPD）分解被用来使适应的声音更稳定。说话人适应实验是在一系列适应话语数下进行的。此外，从1）女性到女性，2）男性到女性和3）女性到男性的演讲者调整。客观测量和主观测试表明，在适应性数据极其有限的情况下，具有LRPD分解的LN表现最稳定，而具有仅200个适应话语的最佳说话人适应（SA）模型与1000个话语训练的说话人相关（SD）与目标说话人的自然和相似。

##### URL
[http://arxiv.org/abs/1803.02445](http://arxiv.org/abs/1803.02445)

##### PDF
[http://arxiv.org/pdf/1803.02445](http://arxiv.org/pdf/1803.02445)

