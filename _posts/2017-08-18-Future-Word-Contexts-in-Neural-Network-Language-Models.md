---
layout: post
title: "Future Word Contexts in Neural Network Language Models"
date: 2017-08-18 13:11:22
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Xie Chen, Xunying Liu, Anton Ragni, Yu Wang, Mark Gales
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, bidirectional recurrent network language models (bi-RNNLMs) have been shown to outperform standard, unidirectional, recurrent neural network language models (uni-RNNLMs) on a range of speech recognition tasks. This indicates that future word context information beyond the word history can be useful. However, bi-RNNLMs pose a number of challenges as they make use of the complete previous and future word context information. This impacts both training efficiency and their use within a lattice rescoring framework. In this paper these issues are addressed by proposing a novel neural network structure, succeeding word RNNLMs (su-RNNLMs). Instead of using a recurrent unit to capture the complete future word contexts, a feedforward unit is used to model a finite number of succeeding, future, words. This model can be trained much more efficiently than bi-RNNLMs and can also be used for lattice rescoring. Experimental results on a meeting transcription task (AMI) show the proposed model consistently outperformed uni-RNNLMs and yield only a slight degradation compared to bi-RNNLMs in N-best rescoring. Additionally, performance improvements can be obtained using lattice rescoring and subsequent confusion network decoding.

##### Abstract (translated by Google)
最近，双向递归网络语言模型（bi-RNNLM）已经被证明在一系列语音识别任务上优于标准的单向递归神经网络语言模型（uni-RNNLM）。这表明超越单词历史的未来单词上下文信息可能是有用的。然而，双RNNLM在利用完整的以前和未来的单词上下文信息时提出了许多挑战。这会影响训练效率和在格子再​​分析框架中的使用。在本文中，通过提出一种新颖的神经网络结构 - 后继词RNNLMs（su-RNNLMs）来解决这些问题。而不是使用经常性的单位来捕捉未来完整的单词上下文，而是使用一个前馈单元来模拟有限数量的成功，将来的单词。这个模型可以比双RNNLM更有效地训练，也可以用于格子重新分割。在会议转录任务（AMI）上的实验结果表明，所提出的模型一贯胜过uni-RNNLMs，并且产生与双N-RNNLMs在N-最佳重新分组中相比仅略微降低。另外，使用格子重新分类和随后的混淆网络解码可以获得性能改进。

##### URL
[https://arxiv.org/abs/1708.05592](https://arxiv.org/abs/1708.05592)

##### PDF
[https://arxiv.org/pdf/1708.05592](https://arxiv.org/pdf/1708.05592)

