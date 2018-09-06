---
layout: post
title: "Unsupervised Statistical Machine Translation"
date: 2018-09-04 23:22:28
categories: arXiv_AI
tags: arXiv_AI Embedding NMT Language_Model
author: Mikel Artetxe, Gorka Labaka, Eneko Agirre
mathjax: true
---

* content
{:toc}

##### Abstract
While modern machine translation has relied on large parallel corpora, a recent line of work has managed to train Neural Machine Translation (NMT) systems from monolingual corpora only (Artetxe et al., 2018c; Lample et al., 2018). Despite the potential of this approach for low-resource settings, existing systems are far behind their supervised counterparts, limiting their practical interest. In this paper, we propose an alternative approach based on phrase-based Statistical Machine Translation (SMT) that significantly closes the gap with supervised systems. Our method profits from the modular architecture of SMT: we first induce a phrase table from monolingual corpora through cross-lingual embedding mappings, combine it with an n-gram language model, and fine-tune hyperparameters through an unsupervised MERT variant. In addition, iterative backtranslation improves results further, yielding, for instance, 14.08 and 26.22 BLEU points in WMT 2014 English-German and English-French, respectively, an improvement of more than 7-10 BLEU points over previous unsupervised systems, and closing the gap with supervised SMT (Moses trained on Europarl) down to 2-5 BLEU points. Our implementation is available at https://github.com/artetxem/monoses

##### Abstract (translated by Google)
虽然现代机器翻译依赖于大型平行语料库，但最近的一系列工作已经设法仅从单语语料库中训练神经机器翻译（NMT）系统（Artetxe等，2018c; Lample等，2018）。尽管这种方法有可能用于低资源环境，但现有系统远远落后于受监管的系统，限制了它们的实际利益。在本文中，我们提出了一种基于短语的统计机器翻译（SMT）的替代方法，该方法显着缩小了与监督系统的差距。我们的方法从SMT的模块化体系结构中获益：我们首先通过跨语言嵌入映射从单语语料库中引入短语表，将其与n-gram语言模型相结合，并通过无监督的MERT变体微调超参数。此外，迭代反向翻译进一步改善了结果，例如，分别在WMT 2014英语 - 德语和英语 - 法语中产生了14.08和26.22个BLEU点，比先前的无监督系统提高了7-10个BLEU点，并且关闭了与受监督的SMT（摩西训练Europarl）的差距低至2-5 BLEU分。我们的实现可以在https://github.com/artetxem/monoses上找到

##### URL
[http://arxiv.org/abs/1809.01272](http://arxiv.org/abs/1809.01272)

##### PDF
[http://arxiv.org/pdf/1809.01272](http://arxiv.org/pdf/1809.01272)

