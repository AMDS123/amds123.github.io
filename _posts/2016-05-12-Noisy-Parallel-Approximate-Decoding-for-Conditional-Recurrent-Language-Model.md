---
layout: post
title: "Noisy Parallel Approximate Decoding for Conditional Recurrent Language Model"
date: 2016-05-12 14:39:50
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Language_Model Recognition
author: Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in conditional recurrent language modelling have mainly focused on network architectures (e.g., attention mechanism), learning algorithms (e.g., scheduled sampling and sequence-level training) and novel applications (e.g., image/video description generation, speech recognition, etc.) On the other hand, we notice that decoding algorithms/strategies have not been investigated as much, and it has become standard to use greedy or beam search. In this paper, we propose a novel decoding strategy motivated by an earlier observation that nonlinear hidden layers of a deep neural network stretch the data manifold. The proposed strategy is embarrassingly parallelizable without any communication overhead, while improving an existing decoding algorithm. We extensively evaluate it with attention-based neural machine translation on the task of En->Cz translation.

##### Abstract (translated by Google)
最近在条件循环语言建模方面的进展主要集中在网络体系结构（如注意机制），学习算法（例如调度采样和序列级别训练）和新颖应用（例如图像/视频描述生成，语音识别等）上。 ）另一方面，我们注意到解码算法/策略还没有得到太多的研究，使用贪婪或者波束搜索已经成为标准。在本文中，我们提出了一个新的解码策略的动机，由一个较早的观察深度神经网络的非线性隐藏层拉伸数据流形。所提出的策略是令人尴尬的可并行而没有任何通信开销，同时改进现有的解码算法。我们在注重神经机器翻译的基础上对En-> Cz的翻译进行了广泛的评估。

##### URL
[https://arxiv.org/abs/1605.03835](https://arxiv.org/abs/1605.03835)

##### PDF
[https://arxiv.org/pdf/1605.03835](https://arxiv.org/pdf/1605.03835)

