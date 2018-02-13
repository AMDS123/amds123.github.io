---
layout: post
title: "Understanding Recurrent Neural State Using Memory Signatures"
date: 2018-02-11 20:59:56
categories: arXiv_CL
tags: arXiv_CL Knowledge RNN Language_Model
author: Skanda Koppula, Khe Chai Sim, Kean Chin
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate a network visualization technique to analyze the recurrent state inside the LSTMs/GRUs used commonly in language and acoustic models. Interpreting intermediate state and network activations inside end-to-end models remains an open challenge. Our method allows users to understand exactly how much and what history is encoded inside recurrent state in grapheme sequence models. Our procedure trains multiple decoders that predict prior input history. Compiling results from these decoders, a user can obtain a signature of the recurrent kernel that characterizes its memory behavior. We demonstrate this method's usefulness in revealing information divergence in the bases of recurrent factorized kernels, visualizing the character-level differences between the memory of n-gram and recurrent language models, and extracting knowledge of history encoded in the layers of grapheme-based end-to-end ASR networks.

##### Abstract (translated by Google)
我们展示了一种网络可视化技术来分析语言和声学模型中常用的LSTMs / GRUs内部的复发状态。解释端到端模型中的中间状态和网络激活仍然是一个公开挑战。我们的方法允许用户在字形序列模型中准确了解历史在经常状态下编码的数量和历史。我们的程序训练多个预测先前输入历史的解码器。编译来自这些解码器的结果，用户可以获得表征其存储器行为的经常性内核的签名。我们证明了这种方法在反复分解因子化核心的基础上揭示信息分歧，可视化n-gram记忆与循环语言模型之间的字符级差异，提取基于字形的终端用户层编码的历史知识，端到端的ASR网络。

##### URL
[http://arxiv.org/abs/1802.03816](http://arxiv.org/abs/1802.03816)

##### PDF
[http://arxiv.org/pdf/1802.03816](http://arxiv.org/pdf/1802.03816)

