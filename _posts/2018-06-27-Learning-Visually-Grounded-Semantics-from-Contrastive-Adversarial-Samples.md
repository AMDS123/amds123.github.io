---
layout: post
title: "Learning Visually-Grounded Semantics from Contrastive Adversarial Samples"
date: 2018-06-27 08:58:57
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Knowledge Caption Embedding Quantitative
author: Haoyue Shi, Jiayuan Mao, Tete Xiao, Yuning Jiang, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of grounding distributional representations of texts on the visual domain, namely visual-semantic embeddings (VSE for short). Begin with an insightful adversarial attack on VSE embeddings, we show the limitation of current frameworks and image-text datasets (e.g., MS-COCO) both quantitatively and qualitatively. The large gap between the number of possible constitutions of real-world semantics and the size of parallel data, to a large extent, restricts the model to establish the link between textual semantics and visual concepts. We alleviate this problem by augmenting the MS-COCO image captioning datasets with textual contrastive adversarial samples. These samples are synthesized using linguistic rules and the WordNet knowledge base. The construction procedure is both syntax- and semantics-aware. The samples enforce the model to ground learned embeddings to concrete concepts within the image. This simple but powerful technique brings a noticeable improvement over the baselines on a diverse set of downstream tasks, in addition to defending known-type adversarial attacks. We release the codes at https://github.com/ExplorerFreda/VSE-C.

##### Abstract (translated by Google)
我们研究视觉领域文本分布表示的基础问题，即视觉语义嵌入（visual-semantic embedding，简称VSE）。从对VSE嵌入的有洞察力的对抗攻击开始，我们从数量和质量上展示了当前框架和图像文本数据集（例如MS-COCO）的局限性。现实世界语义的可能构成数量与并行数据的大小之间的巨大差距在很大程度上限制了模型建立文本语义和视觉概念之间的联系。我们通过用文本对比对抗样本增强MS-COCO图像字幕数据集来缓解这个问题。这些样本是使用语言规则和WordNet知识库合成的。构造过程既是语法语义又是语义知识。这些样本强制模型将学习的嵌入基础映射到图像中的具体概念。这种简单而强大的技术除了可以防范已知类型的敌对攻击外，还可以显着改善各种下游任务的基线。我们在https://github.com/ExplorerFreda/VSE-C上发布代码。

##### URL
[http://arxiv.org/abs/1806.10348](http://arxiv.org/abs/1806.10348)

##### PDF
[http://arxiv.org/pdf/1806.10348](http://arxiv.org/pdf/1806.10348)

