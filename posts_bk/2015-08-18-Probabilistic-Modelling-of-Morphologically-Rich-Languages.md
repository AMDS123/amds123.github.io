---
layout: post
title: "Probabilistic Modelling of Morphologically Rich Languages"
date: 2015-08-18 10:29:10
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Jan A. Botha
mathjax: true
---

* content
{:toc}

##### Abstract
This thesis investigates how the sub-structure of words can be accounted for in probabilistic models of language. Such models play an important role in natural language processing tasks such as translation or speech recognition, but often rely on the simplistic assumption that words are opaque symbols. This assumption does not fit morphologically complex language well, where words can have rich internal structure and sub-word elements are shared across distinct word forms. Our approach is to encode basic notions of morphology into the assumptions of three different types of language models, with the intention that leveraging shared sub-word structure can improve model performance and help overcome data sparsity that arises from morphological processes. In the context of n-gram language modelling, we formulate a new Bayesian model that relies on the decomposition of compound words to attain better smoothing, and we develop a new distributed language model that learns vector representations of morphemes and leverages them to link together morphologically related words. In both cases, we show that accounting for word sub-structure improves the models' intrinsic performance and provides benefits when applied to other tasks, including machine translation. We then shift the focus beyond the modelling of word sequences and consider models that automatically learn what the sub-word elements of a given language are, given an unannotated list of words. We formulate a novel model that can learn discontiguous morphemes in addition to the more conventional contiguous morphemes that most previous models are limited to. This approach is demonstrated on Semitic languages, and we find that modelling discontiguous sub-word structures leads to improvements in the task of segmenting words into their contiguous morphemes.

##### Abstract (translated by Google)
本文研究语言的概率模型如何能够解释词的子结构。这些模型在翻译或语音识别等自然语言处理任务中起着重要的作用，但往往依赖于单词是不透明符号的简单假设。这个假设不适合形态复杂的语言，词汇可以有丰富的内部结构，分词单元在不同的单词形式之间共享。我们的方法是将形态学的基本概念编码成三种不同类型的语言模型的假设，意图是利用共享的子词结构可以提高模型性能并帮助克服形态学过程中产生的数据稀疏性。在n元语言建模的背景下，我们制定了一个新的贝叶斯模型，依靠复合词的分解，以获得更好的平滑，我们开发了一个新的分布式语言模型，学习语素的矢量表示，并利用它们形态连接在一起相关词汇。在这两种情况下，我们都表明，会计词的子结构提高了模型的内在性能，并提供了应用于其他任务，包括机器翻译的好处。然后，我们将焦点转移到单词序列建模之外，并考虑模型自动学习给定语言的子词元素，给定一个未注释的单词列表。我们制定了一个新的模式，可以学习不连续的语素，除了大多数以前的模型所限制的更传统的连续语素之外。这种方法在闪语语言中得到了证明，我们发现建模不连续的子词结构可以改善将单词分割成连续语素的任务。

##### URL
[https://arxiv.org/abs/1508.04271](https://arxiv.org/abs/1508.04271)

##### PDF
[https://arxiv.org/pdf/1508.04271](https://arxiv.org/pdf/1508.04271)

