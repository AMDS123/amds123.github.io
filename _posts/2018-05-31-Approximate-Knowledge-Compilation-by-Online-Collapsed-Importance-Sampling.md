---
layout: post
title: "Approximate Knowledge Compilation by Online Collapsed Importance Sampling"
date: 2018-05-31 17:13:13
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference
author: Tal Friedman, Guy Van den Broeck
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce collapsed compilation, a novel approximate inference algorithm for discrete probabilistic graphical models. It is a collapsed sampling algorithm that incrementally selects which variable to sample next based on the partial sample obtained so far. This online collapsing, together with knowledge compilation inference on the remaining variables, naturally exploits local structure and context- specific independence in the distribution. These properties are naturally exploited in exact inference, but are difficult to harness for approximate inference. More- over, by having a partially compiled circuit available during sampling, collapsed compilation has access to a highly effective proposal distribution for importance sampling. Our experimental evaluation shows that collapsed compilation performs well on standard benchmarks. In particular, when the amount of exact inference is equally limited, collapsed compilation is competitive with the state of the art, and outperforms it on several benchmarks.

##### Abstract (translated by Google)
我们介绍了折叠编译，一种用于离散概率图模型的新近似推理算法。这是一个折叠采样算法，它基于迄今为止获得的部分样本逐步选择要采样的变量。这种在线崩溃以及关于其余变量的知识编制推断，自然地利用了分布中的局部结构和特定环境的独立性。这些属性在确切推理中被自然地利用，但是难以用于近似推理。此外，通过在采样期间提供部分编译电路，崩溃的编译可以获得针对重要性采样的高效提案分发。我们的实验评估显示，崩溃的编译在标准基准测试中表现良好。特别是，当精确推断的数量同样有限时，崩溃的编译与现有技术相比具有竞争性，并且在若干基准测试中胜出。

##### URL
[http://arxiv.org/abs/1805.12565](http://arxiv.org/abs/1805.12565)

##### PDF
[http://arxiv.org/pdf/1805.12565](http://arxiv.org/pdf/1805.12565)

