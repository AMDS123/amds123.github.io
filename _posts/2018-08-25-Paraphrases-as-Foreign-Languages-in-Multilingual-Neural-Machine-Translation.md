---
layout: post
title: "Paraphrases as Foreign Languages in Multilingual Neural Machine Translation"
date: 2018-08-25 15:20:30
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zhong Zhou, Matthias Sperber, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Using paraphrases, the expression of the same semantic meaning in different words, to improve generalization and translation performance is often useful. However, prior works only explore the use of paraphrases at the word or phrase level, not at the sentence or document level. Unlike previous works, we use different translations of the whole training data that are consistent in structure as paraphrases at the corpus level. Our corpus contains parallel paraphrases in multiple languages from various sources. We treat paraphrases as foreign languages, tag source sentences with paraphrase labels, and train in the style of multilingual Neural Machine Translation (NMT). Experimental results indicate that adding paraphrases improves the rare word translation, increases entropy and diversity in lexical choice. Moreover, adding the source paraphrases improves translation performance more effectively than adding the target paraphrases. Combining both the source and the target paraphrases boosts performance further; combining paraphrases with multilingual data also helps but has mixed performance. We achieve a BLEU score of 57.2 for French-to-English translation, training on 24 paraphrases of the Bible, which is ~+27 above the WMT'14 baseline.

##### Abstract (translated by Google)
使用释义，在不同的词语中表达相同的语义，以提高泛化和翻译性能通常是有用的。但是，之前的作品只探讨在单词或短语级别使用释义，而不是在句子或文档级别。与以前的作品不同，我们使用整个训练数据的不同翻译，这些翻译在结构上与在语料库级别的释义一致。我们的语料库包含来自不同来源的多种语言的并行释义。我们将释义视为外语，用复述标签标记源句，并以多语言神经机器翻译（NMT）的方式训练。实验结果表明，添加释义可以改善词汇的罕见翻译，提高词汇选择的熵和多样性。此外，与添加目标释义相比，添加源释义可以更有效地提高翻译性能。结合源语和目标语言可以进一步提高性能;将释义与多语言数据相结合也有所帮助，但性能参差不齐。我们对法语到英语的翻译达到了57.2的BLEU分数，对24个圣经释义进行了培训，比WMT'14基线高出+ 27。

##### URL
[http://arxiv.org/abs/1808.08438](http://arxiv.org/abs/1808.08438)

##### PDF
[http://arxiv.org/pdf/1808.08438](http://arxiv.org/pdf/1808.08438)

