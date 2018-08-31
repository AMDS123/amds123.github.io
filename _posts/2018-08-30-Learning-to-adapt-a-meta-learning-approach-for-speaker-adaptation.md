---
layout: post
title: "Learning to adapt: a meta-learning approach for speaker adaptation"
date: 2018-08-30 11:47:07
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Ond&#x159;ej Klejch, Joachim Fainberg, Peter Bell
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of automatic speech recognition systems can be improved by adapting an acoustic model to compensate for the mismatch between training and testing conditions, for example by adapting to unseen speakers. The success of speaker adaptation methods relies on selecting weights that are suitable for adaptation and using good adaptation schedules to update these weights in order not to overfit to the adaptation data. In this paper we investigate a principled way of adapting all the weights of the acoustic model using a meta-learning. We show that the meta-learner can learn to perform supervised and unsupervised speaker adaptation and that it outperforms a strong baseline adapting LHUC parameters when adapting a DNN AM with 1.5M parameters. We also report initial experiments on adapting TDNN AMs, where the meta-learner achieves comparable performance with LHUC.

##### Abstract (translated by Google)
通过调整声学模型来补偿训练和测试条件之间的不匹配，例如通过适应看不见的扬声器，可以改善自动语音识别系统的性能。说话者自适应方法的成功依赖于选择适合于自适应的权重并使用良好的自适应调度来更新这些权重以便不过度适应自适应数据。在本文中，我们研究了使用元学习来调整声学模型的所有权重的原理方法。我们表明，元学习者可以学习执行有监督和无监督的说话者适应，并且当适应具有1.5M参数的DNN AM时，它优于适应LHUC参数的强基线。我们还报告了关于适应TDNN AM的初步实验，其中元学习者实现了与LHUC相当的性能。

##### URL
[http://arxiv.org/abs/1808.10239](http://arxiv.org/abs/1808.10239)

##### PDF
[http://arxiv.org/pdf/1808.10239](http://arxiv.org/pdf/1808.10239)

