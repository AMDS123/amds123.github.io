---
layout: post
title: "Phrase-Based & Neural Unsupervised Machine Translation"
date: 2018-08-13 22:50:37
categories: arXiv_CL
tags: arXiv_CL NMT Language_Model
author: Guillaume Lample, Myle Ott, Alexis Conneau, Ludovic Denoyer, Marc&#x27;Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
Machine translation systems achieve near human-level performance on some languages, yet their effectiveness strongly relies on the availability of large amounts of parallel sentences, which hinders their applicability to the majority of language pairs. This work investigates how to learn to translate when having access to only large monolingual corpora in each language. We propose two model variants, a neural and a phrase-based model. Both versions leverage a careful initialization of the parameters, the denoising effect of language models and automatic generation of parallel data by iterative back-translation. These models are significantly better than methods from the literature, while being simpler and having fewer hyper-parameters. On the widely used WMT'14 English-French and WMT'16 German-English benchmarks, our models respectively obtain 28.1 and 25.2 BLEU points without using a single parallel sentence, outperforming the state of the art by more than 11 BLEU points. On low-resource languages like English-Urdu and English-Romanian, our methods achieve even better results than semi-supervised and supervised approaches leveraging the paucity of available bitexts. Our code for NMT and PBSMT is publicly available.

##### Abstract (translated by Google)
机器翻译系统在某些语言上实现了接近人类的性能，但其有效性强烈依赖于大量并行句子的可用性，这阻碍了它们适用于大多数语言对。这项工作调查了如何在只能访问每种语言的大型单语语料库时学习翻译。我们提出了两种模型变体，一种神经模型和一种基于短语的模型。两个版本都利用参数的仔细初始化，语言模型的去噪效果以及通过迭代反向翻译自动生成并行数据。这些模型明显优于文献中的方法，同时更简单且具有更少的超参数。在广泛使用的WMT'14英语 - 法语和WMT'16德语 - 英语基准测试中，我们的模型分别在不使用单个平行句的情况下获得28.1和25.2个BLEU点，超过11个BLEU点的技术水平。在英语 - 乌尔都语和英语 - 罗马尼亚语等低资源语言中，我们的方法比半监督和监督方法获得更好的结果，充分利用了可用的bitexts。我们的NMT和PBSMT代码是公开的。

##### URL
[http://arxiv.org/abs/1804.07755](http://arxiv.org/abs/1804.07755)

##### PDF
[http://arxiv.org/pdf/1804.07755](http://arxiv.org/pdf/1804.07755)

