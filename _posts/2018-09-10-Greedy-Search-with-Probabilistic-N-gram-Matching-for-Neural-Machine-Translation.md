---
layout: post
title: "Greedy Search with Probabilistic N-gram Matching for Neural Machine Translation"
date: 2018-09-10 04:41:44
categories: arXiv_CL
tags: arXiv_CL NMT Inference
author: Chenze Shao, Yang Feng, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models are usually trained with the word-level loss using the teacher forcing algorithm, which not only evaluates the translation improperly but also suffers from exposure bias. Sequence-level training under the reinforcement framework can mitigate the problems of the word-level loss, but its performance is unstable due to the high variance of the gradient estimation. On these grounds, we present a method with a differentiable sequence-level training objective based on probabilistic n-gram matching which can avoid the reinforcement framework. In addition, this method performs greedy search in the training which uses the predicted words as context just as at inference to alleviate the problem of exposure bias. Experiment results on the NIST Chinese-to-English translation tasks show that our method significantly outperforms the reinforcement-based algorithms and achieves an improvement of 1.5 BLEU points on average over a strong baseline system.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型通常使用教师强制算法训练单词级别的丢失，这不仅不正确地评估翻译，而且还受到暴露偏差的影响。强化框架下的序列级训练可以缓解单词级丢失的问题，但由于梯度估计的高方差，其性能不稳定。基于这些理由，我们提出了一种基于概率n-gram匹配的可区分序列级训练目标的方法，该方法可以避免强化框架。另外，该方法在训练中进行贪婪搜索，该训练使用预测的单词作为上下文，与推理一样，以减轻曝光偏差的问题。 NIST汉英翻译任务的实验结果表明，我们的方法明显优于基于强化的算法，并且在强基线系统上平均实现了1.5 BLEU点的改进。

##### URL
[http://arxiv.org/abs/1809.03132](http://arxiv.org/abs/1809.03132)

##### PDF
[http://arxiv.org/pdf/1809.03132](http://arxiv.org/pdf/1809.03132)

