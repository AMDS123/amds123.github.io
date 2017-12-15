---
layout: post
title: "Story Generation from Sequence of Independent Short Descriptions"
date: 2017-08-21 13:25:21
categories: arXiv_CL
tags: arXiv_CL Summarization RNN Deep_Learning
author: Parag Jain, Priyanka Agrawal, Abhijit Mishra, Mohak Sukhwani, Anirban Laha, Karthik Sankaranarayanan
mathjax: true
---

* content
{:toc}

##### Abstract
Existing Natural Language Generation (NLG) systems are weak AI systems and exhibit limited capabilities when language generation tasks demand higher levels of creativity, originality and brevity. Effective solutions or, at least evaluations of modern NLG paradigms for such creative tasks have been elusive, unfortunately. This paper introduces and addresses the task of coherent story generation from independent descriptions, describing a scene or an event. Towards this, we explore along two popular text-generation paradigms -- (1) Statistical Machine Translation (SMT), posing story generation as a translation problem and (2) Deep Learning, posing story generation as a sequence to sequence learning problem. In SMT, we chose two popular methods such as phrase based SMT (PB-SMT) and syntax based SMT (SYNTAX-SMT) to `translate' the incoherent input text into stories. We then implement a deep recurrent neural network (RNN) architecture that encodes sequence of variable length input descriptions to corresponding latent representations and decodes them to produce well formed comprehensive story like summaries. The efficacy of the suggested approaches is demonstrated on a publicly available dataset with the help of popular machine translation and summarization evaluation metrics.

##### Abstract (translated by Google)
现有的自然语言生成（NLG）系统是弱的AI系统，并且在语言生成任务需要更高水平的创造性，原创性和简洁性时展现出有限的能力。不幸的是，有效的解决方案，或者至少是对这种创造性任务的现代NLG范式的评估，已经是难以捉摸的了。本文从独立描述引入和处理连贯故事生成的任务，描述一个场景或一个事件。为此，我们探讨了两种流行的文本生成模式：（1）统计机器翻译（SMT），将故事生成作为翻译问题;（2）深度学习，将故事生成作为序列学习问题的序列。在SMT中，我们选择了基于短语的SMT（PB-SMT）和基于语法的SMT（SYNTAX-SMT）两种流行的方法来将不相干的输入文本“翻译”成故事。然后，我们实现一种深度递归神经网络（RNN）架构，将可变长度输入描述的序列编码为相应的潜在表示，并对它们进行解码，以产生类似摘要的良好综合性故事。所提出的方法的功效在公众可获得的数据集上借助流行的机器翻译和摘要评估度量来演示。

##### URL
[https://arxiv.org/abs/1707.05501](https://arxiv.org/abs/1707.05501)

##### PDF
[https://arxiv.org/pdf/1707.05501](https://arxiv.org/pdf/1707.05501)

