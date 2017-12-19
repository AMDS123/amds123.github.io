---
layout: post
title: "Beyond Word-based Language Model in Statistical Machine Translation"
date: 2015-02-05 07:42:18
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Jiajun Zhang, Shujie Liu, Mu Li, Ming Zhou, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
Language model is one of the most important modules in statistical machine translation and currently the word-based language model dominants this community. However, many translation models (e.g. phrase-based models) generate the target language sentences by rendering and compositing the phrases rather than the words. Thus, it is much more reasonable to model dependency between phrases, but few research work succeed in solving this problem. In this paper, we tackle this problem by designing a novel phrase-based language model which attempts to solve three key sub-problems: 1, how to define a phrase in language model; 2, how to determine the phrase boundary in the large-scale monolingual data in order to enlarge the training set; 3, how to alleviate the data sparsity problem due to the huge vocabulary size of phrases. By carefully handling these issues, the extensive experiments on Chinese-to-English translation show that our phrase-based language model can significantly improve the translation quality by up to +1.47 absolute BLEU score.

##### Abstract (translated by Google)
语言模型是统计机器翻译中最重要的模块之一，目前基于单词的语言模型主导着这个社区。然而，许多翻译模型（例如，基于短语的模型）通过渲染和合成短语而不是单词来生成目标语言句子。因此，对短语之间的依赖进行建模是比较合理的，但是很少有研究成功地解决这个问题。在本文中，我们通过设计一个新颖的基于短语的语言模型来解决这个问题，该模型试图解决三个关键的子问题：1，如何在语言模型中定义一个短语; 2，如何确定大规模单语数据中的词组边界以扩大训练集; 3，由于词组庞大的词汇量，如何缓解数据稀疏问题。通过仔细处理这些问题，中英文翻译的广泛实验表明，我们的基于短语的语言模型可以显着提高翻译质量达到绝对BLEU得分+1.47。

##### URL
[https://arxiv.org/abs/1502.01446](https://arxiv.org/abs/1502.01446)

##### PDF
[https://arxiv.org/pdf/1502.01446](https://arxiv.org/pdf/1502.01446)

