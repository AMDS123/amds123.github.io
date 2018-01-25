---
layout: post
title: "Evaluating Layers of Representation in Neural Machine Translation on Part-of-Speech and Semantic Tagging Tasks"
date: 2018-01-23 20:59:55
categories: arXiv_CL
tags: arXiv_CL GAN Represenation_Learning NMT Quantitative
author: Yonatan Belinkov, Llu&#xed;s M&#xe0;rquez, Hassan Sajjad, Nadir Durrani, Fahim Dalvi, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
While neural machine translation (NMT) models provide improved translation quality in an elegant, end-to-end framework, it is less clear what they learn about language. Recent work has started evaluating the quality of vector representations learned by NMT models on morphological and syntactic tasks. In this paper, we investigate the representations learned at different layers of NMT encoders. We train NMT systems on parallel data and use the trained models to extract features for training a classifier on two tasks: part-of-speech and semantic tagging. We then measure the performance of the classifier as a proxy to the quality of the original NMT model for the given task. Our quantitative analysis yields interesting insights regarding representation learning in NMT models. For instance, we find that higher layers are better at learning semantics while lower layers tend to be better for part-of-speech tagging. We also observe little effect of the target language on source-side representations, especially with higher quality NMT models.

##### Abstract (translated by Google)
尽管神经机器翻译（NMT）模型在优雅的端到端框架中提供了改进的翻译质量，但是他们对语言的了解却不太清楚。最近的工作已经开始评估NMT模型在形态和句法任务上学习的向量表示的质量。在本文中，我们研究在不同层次的NMT编码器上学到的表示。我们训练NMT系统的并行数据，并使用训练过的模型提取特征来训练分类器的两个任务：词性和语义标记。然后，我们测量分类器的性能，作为给定任务的原始NMT模型的质量的代理。我们的定量分析产生有趣的洞察力，在NMT模型中的表示学习。例如，我们发现较高层的学习语义较好，而较低层往往更适合词性标注。我们也观察到目标语言对源端表示的影响很小，特别是对于更高质量的NMT模型。

##### URL
[http://arxiv.org/abs/1801.07772](http://arxiv.org/abs/1801.07772)

##### PDF
[http://arxiv.org/pdf/1801.07772](http://arxiv.org/pdf/1801.07772)

