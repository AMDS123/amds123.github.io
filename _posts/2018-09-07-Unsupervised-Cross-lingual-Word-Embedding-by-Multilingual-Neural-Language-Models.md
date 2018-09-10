---
layout: post
title: "Unsupervised Cross-lingual Word Embedding by Multilingual Neural Language Models"
date: 2018-09-07 04:17:40
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model
author: Takashi Wada, Tomoharu Iwata
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an unsupervised method to obtain cross-lingual embeddings without any parallel data or pre-trained word embeddings. The proposed model, which we call multilingual neural language models, takes sentences of multiple languages as an input. The proposed model contains bidirectional LSTMs that perform as forward and backward language models, and these networks are shared among all the languages. The other parameters, i.e. word embeddings and linear transformation between hidden states and outputs, are specific to each language. The shared LSTMs can capture the common sentence structure among all languages. Accordingly, word embeddings of each language are mapped into a common latent space, making it possible to measure the similarity of words across multiple languages. We evaluate the quality of the cross-lingual word embeddings on a word alignment task. Our experiments demonstrate that our model can obtain cross-lingual embeddings of much higher quality than existing unsupervised models when only a small amount of monolingual data (i.e. 50k sentences) are available, or the domains of monolingual data are different across languages.

##### Abstract (translated by Google)
我们提出了一种无监督的方法来获得跨语言嵌入，而无需任何并行数据或预先训练的字嵌入。所提出的模型，我们称之为多语言神经语言模型，将多种语言的句子作为输入。所提出的模型包含作为前向和后向语言模型的双向LSTM，并且这些网络在所有语言之间共享。其他参数，即字嵌入和隐藏状态与输出之间的线性变换，是每种语言特有的。共享LSTM可以捕获所有语言中的常用句子结构。因此，每种语言的单词嵌入被映射到共同的潜在空间，使得可以测量跨多种语言的单词的相似性。我们在单词对齐任务上评估跨语言嵌入的质量。我们的实验证明，当只有少量的单语数据（即50k句子）可用时，我们的模型可以获得比现有无监督模型更高质量的跨语言嵌入，或者单语数据的域在不同语言中是不同的。

##### URL
[https://arxiv.org/abs/1809.02306](https://arxiv.org/abs/1809.02306)

##### PDF
[https://arxiv.org/pdf/1809.02306](https://arxiv.org/pdf/1809.02306)

