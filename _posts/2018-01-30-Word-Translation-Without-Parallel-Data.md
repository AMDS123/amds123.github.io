---
layout: post
title: "Word Translation Without Parallel Data"
date: 2018-01-30 14:41:51
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Alexis Conneau, Guillaume Lample, Marc&#x27;Aurelio Ranzato, Ludovic Denoyer, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for learning cross-lingual word embeddings have relied on bilingual dictionaries or parallel corpora. Recent studies showed that the need for parallel data supervision can be alleviated with character-level information. While these methods showed encouraging results, they are not on par with their supervised counterparts and are limited to pairs of languages sharing a common alphabet. In this work, we show that we can build a bilingual dictionary between two languages without using any parallel corpora, by aligning monolingual word embedding spaces in an unsupervised way. Without using any character information, our model even outperforms existing supervised methods on cross-lingual tasks for some language pairs. Our experiments demonstrate that our method works very well also for distant language pairs, like English-Russian or English-Chinese. We finally describe experiments on the English-Esperanto low-resource language pair, on which there only exists a limited amount of parallel data, to show the potential impact of our method in fully unsupervised machine translation. Our code, embeddings and dictionaries are publicly available.

##### Abstract (translated by Google)
用于学习跨语言单词嵌入的最先进的方法依赖于双语词典或平行语料库。最近的研究表明，并行数据监督的需求可以通过字符级别的信息来缓解。虽然这些方法显示出令人鼓舞的结果，但与受监督的方法并不相同，仅限于使用共同字母表的语言对。在这项工作中，我们表明，我们可以在不使用任何平行语料库的情况下，通过以无监督方式对齐单语词嵌入空间，在两种语言之间建立双语词典。在不使用任何字符信息的情况下，我们的模型甚至超过了对于某些语言对的跨语言任务的现有监督方法。我们的实验表明，我们的方法对远距离语言对也是很好的，比如说英语 - 俄语或英语 - 中文。我们最后描述了英语世界语低资源语言对上的实验，其中只存在有限的并行数据，以显示我们的方法在完全无监督的机器翻译中的潜在影响。我们的代码，嵌入和字典是公开可用的。

##### URL
[http://arxiv.org/abs/1710.04087](http://arxiv.org/abs/1710.04087)

##### PDF
[http://arxiv.org/pdf/1710.04087](http://arxiv.org/pdf/1710.04087)

