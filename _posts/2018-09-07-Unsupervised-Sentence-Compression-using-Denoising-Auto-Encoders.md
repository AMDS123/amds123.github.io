---
layout: post
title: "Unsupervised Sentence Compression using Denoising Auto-Encoders"
date: 2018-09-07 20:56:33
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Thibault F&#xe9;vry, Jason Phang
mathjax: true
---

* content
{:toc}

##### Abstract
In sentence compression, the task of shortening sentences while retaining the original meaning, models tend to be trained on large corpora containing pairs of verbose and compressed sentences. To remove the need for paired corpora, we emulate a summarization task and add noise to extend sentences and train a denoising auto-encoder to recover the original, constructing an end-to-end training regime without the need for any examples of compressed sentences. We conduct a human evaluation of our model on a standard text summarization dataset and show that it performs comparably to a supervised baseline based on grammatical correctness and retention of meaning. Despite being exposed to no target data, our unsupervised models learn to generate imperfect but reasonably readable sentence summaries. Although we underperform supervised models based on ROUGE scores, our models are competitive with a supervised baseline based on human evaluation for grammatical correctness and retention of meaning.

##### Abstract (translated by Google)
在句子压缩中，在保留原始含义的同时缩短句子的任务，模型倾向于在包含多个冗长和压缩句子的大型语料库上训练。为了消除对配对语料库的需要，我们模拟摘要任务并添加噪声以扩展句子并训练去噪自动编码器以恢复原始，构建端到端训练机制而无需任何压缩句子的例子。我们在标准文本摘要数据集上对我们的模型进行人工评估，并表明它与基于语法正确性和意义保留的监督基线相当。尽管没有暴露于目标数据，我们的无监督模型学会生成不完美但合理可读的句子摘要。虽然我们的表现不及基于ROUGE分数的监督模型，但我们的模型与基于人类评估语法正确性和意义保留的监督基线竞争。

##### URL
[http://arxiv.org/abs/1809.02669](http://arxiv.org/abs/1809.02669)

##### PDF
[http://arxiv.org/pdf/1809.02669](http://arxiv.org/pdf/1809.02669)

