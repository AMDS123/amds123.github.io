---
layout: post
title: "The Fine Line between Linguistic Generalization and Failure in Seq2Seq-Attention Models"
date: 2018-05-03 17:45:33
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Noah Weber, Leena Shekhar, Niranjan Balasubramanian
mathjax: true
---

* content
{:toc}

##### Abstract
Seq2Seq based neural architectures have become the go-to architecture to apply to sequence to sequence language tasks. Despite their excellent performance on these tasks, recent work has noted that these models usually do not fully capture the linguistic structure required to generalize beyond the dense sections of the data distribution \cite{ettinger2017towards}, and as such, are likely to fail on samples from the tail end of the distribution (such as inputs that are noisy \citep{belkinovnmtbreak} or of different lengths \citep{bentivoglinmtlength}). In this paper, we look at a model's ability to generalize on a simple symbol rewriting task with a clearly defined structure. We find that the model's ability to generalize this structure beyond the training distribution depends greatly on the chosen random seed, even when performance on the standard test set remains the same. This suggests that a model's ability to capture generalizable structure is highly sensitive. Moreover, this sensitivity may not be apparent when evaluating it on standard test sets.

##### Abstract (translated by Google)
基于Seq2Seq的神经架构已经成为应用于序列语言任务序列的首选架构。尽管他们在这些任务上表现出色，但最近的工作已经注意到这些模型通常不能完全捕捉在数据分布\ cite {ettinger2017towards}的密集部分之外概括所需的语言结构，因此，样本可能会失败从分布的末端（例如嘈杂\ citep {belkinovnmtbreak}或不同长度\ citep {bentivoglinmtlength}）的输入。在本文中，我们考察一个模型在一个简单的符号重写任务上推广并具有明确定义的结构的能力。我们发现，模型在训练分布之外推广这种结构的能力在很大程度上取决于所选择的随机种子，即使标准测试集的性能保持不变。这表明模型捕获可普遍化结构的能力非常敏感。而且，在标准测试集上评估时，这种敏感性可能不明显。

##### URL
[http://arxiv.org/abs/1805.01445](http://arxiv.org/abs/1805.01445)

##### PDF
[http://arxiv.org/pdf/1805.01445](http://arxiv.org/pdf/1805.01445)

