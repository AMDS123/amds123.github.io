---
layout: post
title: "Fundamentals of Recurrent Neural Network and Long Short-Term Memory Network"
date: 2018-08-09 19:31:42
categories: arXiv_CV
tags: arXiv_CV Review Inference RNN
author: Alex Sherstinsky
mathjax: true
---

* content
{:toc}

##### Abstract
Because of their effectiveness in broad practical applications, LSTM networks have received a wealth of coverage in scientific journals, technical blogs, and implementation guides. However, in most articles, the inference formulas for the LSTM network and its parent, RNN, are stated axiomatically, while the training formulas are omitted altogether. In addition, the technique of "unrolling" an RNN is routinely presented without justification throughout the literature. The goal of this paper is to explain the essential RNN and LSTM fundamentals in a single document. Drawing from concepts in signal processing, we formally derive the canonical RNN formulation from differential equations. We then propose and prove a precise statement, which yields the RNN unrolling technique. We also review the difficulties with training the standard RNN and address them by transforming the RNN into the "Vanilla LSTM" network through a series of logical arguments. We provide all equations pertaining to the LSTM system together with detailed descriptions of its constituent entities. Albeit unconventional, our choice of notation and the method for presenting the LSTM system emphasizes ease of understanding. As part of the analysis, we identify new opportunities to enrich the LSTM system and incorporate these extensions into the Vanilla LSTM network, producing the most general LSTM variant to date. The target reader has already been exposed to RNNs and LSTM networks through numerous available resources and is open to an alternative pedagogical approach. A Machine Learning practitioner seeking guidance for implementing our new augmented LSTM model in software for experimentation and research will find the insights and derivations in this tutorial valuable as well.

##### Abstract (translated by Google)
由于LSTM网络在广泛的实际应用中的有效性，因此在科学期刊，技术博客和实施指南中获得了广泛的报道。然而，在大多数文章中，LSTM网络及其父亲RNN的推理公式是公理性地陈述的，而训练公式完全被省略。此外，在整个文献中没有正当理由地常规地呈现“展开”RNN的技术。本文的目的是在单个文档中解释基本的RNN和LSTM基础知识。根据信号处理中的概念，我们从微分方程中正式推导出规范的RNN公式。然后，我们提出并证明了一个精确的陈述，它产生了RNN展开技术。我们还审查了训练标准RNN的困难，并通过一系列逻辑参数将RNN转换为“Vanilla LSTM”网络来解决这些问题。我们提供与LSTM系统有关的所有方程式以及其组成实体的详细描述。虽然非常规，但我们选择的符号和呈现LSTM系统的方法强调易于理解。作为分析的一部分，我们确定了丰富LSTM系统的新机会，并将这些扩展纳入Vanilla LSTM网络，从而产生迄今为止最常见的LSTM变体。目标读者已经通过众多可用资源接触到RNN和LSTM网络，并且可以采用另一种教学方法。机器学习从业者在实验和研究软件中寻求实施我们新的增强LSTM模型的指导，将会发现本教程中的见解和推导也很有价值。

##### URL
[https://arxiv.org/abs/1808.03314](https://arxiv.org/abs/1808.03314)

##### PDF
[https://arxiv.org/pdf/1808.03314](https://arxiv.org/pdf/1808.03314)

