---
layout: post
title: "Conditional End-to-End Audio Transforms"
date: 2018-03-30 20:17:31
categories: arXiv_CL
tags: arXiv_CL CNN RNN
author: Albert Haque, Michelle Guo, Prateek Verma
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end method for transforming audio from one style to another. For the case of speech, by conditioning on speaker identities, we can train a single model to transform words spoken by multiple people into multiple target voices. For the case of music, we can specify musical instruments and achieve the same result. Architecturally, our method is a fully-differentiable sequence-to-sequence model based on convolutional and hierarchical recurrent neural networks. It is designed to capture long-term acoustic dependencies, requires minimal post-processing, and produces realistic audio transforms. Ablation studies confirm that our model can separate speaker and instrument properties from acoustic content at different receptive fields. Empirically, our method achieves competitive performance on community-standard datasets.

##### Abstract (translated by Google)
我们提出了一种将音频从一种风格转换为另一种风格的端到端方法。对于说话的情况，通过对说话人身份进行调节，我们可以训练单一模型，将多个人说出的话语转换为多个目标语音。对于音乐的情况，我们可以指定乐器并获得相同的结果。在体系结构上，我们的方法是一种基于卷积和递阶递归神经网络的完全可微序列 - 序列模型。它旨在捕捉长期声学依赖性，需要最少的后期处理，并产生逼真的音频变换。消融研究证实，我们的模型可以将扬声器和仪器属性与不同感受野的声学内容分开。从经验上讲，我们的方法在社区标准数据集上实现了有竞争力的表现。

##### URL
[http://arxiv.org/abs/1804.00047](http://arxiv.org/abs/1804.00047)

##### PDF
[http://arxiv.org/pdf/1804.00047](http://arxiv.org/pdf/1804.00047)

