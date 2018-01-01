---
layout: post
title: "Detecting Cross-Lingual Plagiarism Using Simulated Word Embeddings"
date: 2017-12-29 11:46:13
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Prediction Detection
author: Victor Thompson
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-lingual plagiarism (CLP) occurs when texts written in one language are translated into a different language and used without acknowledgement. One of the most common methods used for detecting CLP requires online machine translators (such as Google or Microsoft translate) which are not always available, and given that plagiarism detection typically involves large document comparison, the amount of translations would overwhelm an online machine translator, especially when detecting plagiarism over the web. In addition, when translated texts are replaced with their synonyms, using online machine translators to detect CLP would result in poor performance. This paper addresses the problem of cross-lingual plagiarism detection (CLPD) by proposing a model that uses simulated word embeddings to reproduce the predictions of an online machine translator (Google translate) when detecting CLP without relying on online translators. The simulated embeddings comprise of translated words in different languages mapped in a common space, and replicated to increase the prediction probability of retrieving the translations of a word (and their synonyms) from the model. Unlike most existing models, the proposed model does not require parallel corpora, and accommodates multiple languages (multi-lingual). We demonstrated the effectiveness of the proposed model in detecting CLP in standard datasets that contain CLP cases, and evaluated its performance against a state-of-the-art baseline that relies on online machine translator (T+MA model). Evaluation results revealed that the proposed model is not only effective in detecting CLP, it outperformed the baseline. The results indicate that CLP could be detected with state-of-the-art performances by leveraging the prediction accuracy of an internet translator with word embeddings without relying on internet translators.

##### Abstract (translated by Google)
当用一种语言写成的文本被翻译成不同的语言并且没有确认地使用时，出现跨语言抄袭（CLP）。检测CLP最常用的方法之一就是要求在线机器翻译（如Google或Microsoft翻译），这些翻译并不总是可用的，并且由于抄袭检测通常涉及大量的文档比较，所以翻译量将超过在线机器翻译，尤其是当检测到网上的抄袭。另外，当翻译文本被他们的同义词替换时，使用在线机器翻译来检测CLP将会导致较差的性能。本文针对跨语言剽窃检测（CLPD）的问题，提出了一种模型，该模型使用模拟词语嵌入来重现在线机器翻译（Google翻译）在检测CLP时不依赖于在线翻译的预测。模拟嵌入包括映射到公共空间的不同语言的翻译单词，并被复制以提高从模型中检索单词（及其同义词）的翻译的预测概率。与大多数现有的模型不同，所提出的模型不需要平行的语料库，并且适应多种语言（多语言）。我们证明了所提出的模型在包含CLP病例的标准数据集中检测CLP的有效性，并根据依赖在线机器翻译器（T + MA模型）的最先进的基线来评估其性能。评估结果表明，该模型不仅有效检测CLP，还优于基线。结果表明，CLP可以通过利用互联网翻译器的词语嵌入的预测准确性而不依赖于互联网翻译器而利用最新的表演来检测。

##### URL
[https://arxiv.org/abs/1712.10190](https://arxiv.org/abs/1712.10190)

##### PDF
[https://arxiv.org/pdf/1712.10190](https://arxiv.org/pdf/1712.10190)

