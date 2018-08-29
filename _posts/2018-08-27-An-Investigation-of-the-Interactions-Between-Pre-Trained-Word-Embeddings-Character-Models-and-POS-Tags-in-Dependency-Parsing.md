---
layout: post
title: "An Investigation of the Interactions Between Pre-Trained Word Embeddings, Character Models and POS Tags in Dependency Parsing"
date: 2018-08-27 23:11:47
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Aaron Smith, Miryam de Lhoneux, Sara Stymne, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
We provide a comprehensive analysis of the interactions between pre-trained word embeddings, character models and POS tags in a transition-based dependency parser. While previous studies have shown POS information to be less important in the presence of character models, we show that in fact there are complex interactions between all three techniques. In isolation each produces large improvements over a baseline system using randomly initialised word embeddings only, but combining them quickly leads to diminishing returns. We categorise words by frequency, POS tag and language in order to systematically investigate how each of the techniques affects parsing quality. For many word categories, applying any two of the three techniques is almost as good as the full combined system. Character models tend to be more important for low-frequency open-class words, especially in morphologically rich languages, while POS tags can help disambiguate high-frequency function words. We also show that large character embedding sizes help even for languages with small character sets, especially in morphologically rich languages.

##### Abstract (translated by Google)
我们提供了对基于转换的依赖性解析器中预训练的单词嵌入，角色模型和POS标签之间的交互的全面分析。虽然之前的研究表明，在人物模型存在的情况下，POS信息并不那么重要，但事实证明，这三种技术之间存在着复杂的相互作用。在单独使用随机初始化的单词嵌入的基础系统中，每个都会产生很大的改进，但快速组合它们会导致收益递减。我们按频率，POS标签和语言对单词进行分类，以便系统地研究每种技术如何影响解析质量。对于许多单词类别，应用三种技术中的任何两种几乎与完整的组合系统一样好。对于低频率的开放式单词，字符模型往往更为重要，特别是在形态丰富的语言中，而POS标签可以帮助消除高频功能单词的歧义。我们还表明，大字符嵌入大小甚至可以帮助具有小字符集的语言，特别是在形态丰富的语言中。

##### URL
[http://arxiv.org/abs/1808.09060](http://arxiv.org/abs/1808.09060)

##### PDF
[http://arxiv.org/pdf/1808.09060](http://arxiv.org/pdf/1808.09060)

