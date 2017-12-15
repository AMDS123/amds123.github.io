---
layout: post
title: "Assessing the Ability of LSTMs to Learn Syntax-Sensitive Dependencies"
date: 2016-11-04 13:36:32
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Prediction
author: Tal Linzen, Emmanuel Dupoux, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
The success of long short-term memory (LSTM) neural networks in language processing is typically attributed to their ability to capture long-distance statistical regularities. Linguistic regularities are often sensitive to syntactic structure; can such dependencies be captured by LSTMs, which do not have explicit structural representations? We begin addressing this question using number agreement in English subject-verb dependencies. We probe the architecture's grammatical competence both using training objectives with an explicit grammatical target (number prediction, grammaticality judgments) and using language models. In the strongly supervised settings, the LSTM achieved very high overall accuracy (less than 1% errors), but errors increased when sequential and structural information conflicted. The frequency of such errors rose sharply in the language-modeling setting. We conclude that LSTMs can capture a non-trivial amount of grammatical structure given targeted supervision, but stronger architectures may be required to further reduce errors; furthermore, the language modeling signal is insufficient for capturing syntax-sensitive dependencies, and should be supplemented with more direct supervision if such dependencies need to be captured.

##### Abstract (translated by Google)
长期短期记忆（LSTM）神经网络在语言处理中的成功通常归因于它们捕获长距离统计规律的能力。语言规律常常对句法结构敏感; LSTMs可以捕获这样的依赖关系吗，它们没有明确的结构表示？我们开始用英文主谓式依赖关系中的数字协议来解决这个问题。我们通过明确的语法目标（数量预测，语法判断）和使用语言模型来探究架构的语法能力。在强有力的监督设置下，LSTM实现了非常高的总体准确度（小于1％的错误），但是当顺序和结构信息发生冲突时，错误会增加。这种错误的频率在语言建模中急剧上升。我们得出的结论是，LSTM可以在有针对性的监督下获得一个不重要的语法结构，但是可能需要更强大的体系结构来进一步减少错误;此外，语言建模信号不足以捕获对语法敏感的依赖性，并且如果需要捕获这种依赖关系，则应该补充更直接的监督。

##### URL
[https://arxiv.org/abs/1611.01368](https://arxiv.org/abs/1611.01368)

##### PDF
[https://arxiv.org/pdf/1611.01368](https://arxiv.org/pdf/1611.01368)

