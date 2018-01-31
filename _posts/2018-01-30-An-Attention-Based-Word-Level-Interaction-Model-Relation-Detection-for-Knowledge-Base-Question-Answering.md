---
layout: post
title: "An Attention-Based Word-Level Interaction Model: Relation Detection for Knowledge Base Question Answering"
date: 2018-01-30 08:44:19
categories: arXiv_CL
tags: arXiv_CL Knowledge QA Attention CNN Deep_Learning Detection Relation
author: Hongzhi Zhang, Guandong Xu, Xiao Liang, Tinglei Huang, Kun fu
mathjax: true
---

* content
{:toc}

##### Abstract
Relation detection plays a crucial role in Knowledge Base Question Answering (KBQA) because of the high variance of relation expression in the question. Traditional deep learning methods follow an encoding-comparing paradigm, where the question and the candidate relation are represented as vectors to compare their semantic similarity. Max- or average- pooling operation, which compresses the sequence of words into fixed-dimensional vectors, becomes the bottleneck of information. In this paper, we propose to learn attention-based word-level interactions between questions and relations to alleviate the bottleneck issue. Similar to the traditional models, the question and relation are firstly represented as sequences of vectors. Then, instead of merging the sequence into a single vector with pooling operation, soft alignments between words from the question and the relation are learned. The aligned words are subsequently compared with the convolutional neural network (CNN) and the comparison results are merged finally. Through performing the comparison on low-level representations, the attention-based word-level interaction model (ABWIM) relieves the information loss issue caused by merging the sequence into a fixed-dimensional vector before the comparison. The experimental results of relation detection on both SimpleQuestions and WebQuestions datasets show that ABWIM achieves state-of-the-art accuracy, demonstrating its effectiveness.

##### Abstract (translated by Google)
关系检测在知识库问题答案（Knowledge Base Question Answering，简称KBQA）中起着至关重要的作用，因为问题中关系表达的高度方差。传统的深度学习方法遵循编码 - 比较范式，问题和候选关系被表示为向量来比较它们的语义相似性。将单词序列压缩成固定维向量的最大或平均归并操作成为信息的瓶颈。在本文中，我们建议学习基于注意的问题和关系之间的单词级互动来缓解瓶颈问题。问题和关系类似于传统模型，首先表示为向量序列。然后，不是将该序列合并成具有合并操作的单个向量，而是从该问题与该关系中的单词之间的软对齐被学习。随后将对齐的单词与卷积神经网络（CNN）进行比较，最后将比较结果合并。基于关注的词级交互模型（ABWIM）通过对低级表示进行比较，减少了在比较之前将序列合并成固定维向量所引起的信息丢失问题。 SimpleQuestions和WebQuestions数据集的关系检测实验结果表明，ABWIM达到了最新的精度，证明了其有效性。

##### URL
[http://arxiv.org/abs/1801.09893](http://arxiv.org/abs/1801.09893)

##### PDF
[http://arxiv.org/pdf/1801.09893](http://arxiv.org/pdf/1801.09893)

