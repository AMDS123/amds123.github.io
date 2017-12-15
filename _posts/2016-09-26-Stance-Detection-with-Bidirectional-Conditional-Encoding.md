---
layout: post
title: "Stance Detection with Bidirectional Conditional Encoding"
date: 2016-09-26 20:49:16
categories: arXiv_CL
tags: arXiv_CL RNN Detection
author: Isabelle Augenstein, Tim Rocktäschel, Andreas Vlachos, Kalina Bontcheva
mathjax: true
---

* content
{:toc}

##### Abstract
Stance detection is the task of classifying the attitude expressed in a text towards a target such as Hillary Clinton to be "positive", negative" or "neutral". Previous work has assumed that either the target is mentioned in the text or that training data for every target is given. This paper considers the more challenging version of this task, where targets are not always mentioned and no training data is available for the test targets. We experiment with conditional LSTM encoding, which builds a representation of the tweet that is dependent on the target, and demonstrate that it outperforms encoding the tweet and the target independently. Performance is improved further when the conditional model is augmented with bidirectional encoding. We evaluate our approach on the SemEval 2016 Task 6 Twitter Stance Detection corpus achieving performance second best only to a system trained on semi-automatically labelled tweets for the test target. When such weak supervision is added, our approach achieves state-of-the-art results.

##### Abstract (translated by Google)
姿态检测是将文本中表达的态度分类为“正面”，“负面”或“中性”等目标的任务。以前的工作假设文本中提到了目标或者训练数据本文考虑了这个任务的更具挑战性的版本，其中目标并不总是被提及，并且没有训练数据可用于测试目标，我们尝试了有条件的LSTM编码，其构建了鸣叫的表示依赖于目标，并证明它的性能优于独立编码推特和目标，当条件模型增加了双向编码时，性能得到进一步改善我们评估了我们在SemEval 2016任务6上的方法Twitter的姿态检测语料库实现了第二好的性能只有通过半自动标记的tweets为测试目标训练的系统，当这样的弱监督被添加，我们的approac h达到了最先进的结果。

##### URL
[https://arxiv.org/abs/1606.05464](https://arxiv.org/abs/1606.05464)

##### PDF
[https://arxiv.org/pdf/1606.05464](https://arxiv.org/pdf/1606.05464)

