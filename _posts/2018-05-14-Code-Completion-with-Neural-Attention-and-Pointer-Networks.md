---
layout: post
title: "Code Completion with Neural Attention and Pointer Networks"
date: 2018-05-14 15:04:18
categories: arXiv_CL
tags: arXiv_CL Attention RNN Language_Model
author: Jian Li, Yue Wang, Michael R. Lyu, Irwin King
mathjax: true
---

* content
{:toc}

##### Abstract
Intelligent code completion has become an essential research task to accelerate modern software development. To facilitate effective code completion for dynamically-typed programming languages, we apply neural language models by learning from large codebases, and develop a tailored attention mechanism for code completion. However, standard neural language models even with attention mechanism cannot correctly predict the out-of-vocabulary (OoV) words that restrict the code completion performance. In this paper, inspired by the prevalence of locally repeated terms in program source code, and the recently proposed pointer copy mechanism, we propose a pointer mixture network for better predicting OoV words in code completion. Based on the context, the pointer mixture network learns to either generate a within-vocabulary word through an RNN component, or regenerate an OoV word from local context through a pointer component. Experiments on two benchmarked datasets demonstrate the effectiveness of our attention mechanism and pointer mixture network on the code completion task.

##### Abstract (translated by Google)
智能代码完成已经成为加速现代软件开发的重要研究课题。为了促进动态类型编程语言的有效代码完成，我们通过从大型代码库学习来应用神经语言模型，并为代码完成开发量身定制的注意机制。然而，即使有注意机制的标准神经语言模型也不能正确预测限制代码完成性能的词汇外（OoV）词。在本文中，受程序源代码中局部重复术语的普遍性以及最近提出的指针复制机制的启发，我们提出了一个指针混合网络，用于更好地预测代码完成中的OoV字。基于上下文，指针混合网络学习通过RNN组件生成词汇表内词，或者通过指针组件从本地上下文重新生成OoV词。对两个基准数据集的实验证明了我们的注意机制和指针混合网络对代码完成任务的有效性。

##### URL
[http://arxiv.org/abs/1711.09573](http://arxiv.org/abs/1711.09573)

##### PDF
[http://arxiv.org/pdf/1711.09573](http://arxiv.org/pdf/1711.09573)

