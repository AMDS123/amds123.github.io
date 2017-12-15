---
layout: post
title: "Minimally Supervised Written-to-Spoken Text Normalization"
date: 2016-09-21 17:51:11
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Recognition
author: Ke Wu, Kyle Gorman, Richard Sproat
mathjax: true
---

* content
{:toc}

##### Abstract
In speech-applications such as text-to-speech (TTS) or automatic speech recognition (ASR), \emph{text normalization} refers to the task of converting from a \emph{written} representation into a representation of how the text is to be \emph{spoken}. In all real-world speech applications, the text normalization engine is developed---in large part---by hand. For example, a hand-built grammar may be used to enumerate the possible ways of saying a given token in a given language, and a statistical model used to select the most appropriate pronunciation in context. In this study we examine the tradeoffs associated with using more or less language-specific domain knowledge in a text normalization engine. In the most data-rich scenario, we have access to a carefully constructed hand-built normalization grammar that for any given token will produce a set of all possible verbalizations for that token. We also assume a corpus of aligned written-spoken utterances, from which we can train a ranking model that selects the appropriate verbalization for the given context. As a substitute for the carefully constructed grammar, we also consider a scenario with a language-universal normalization \emph{covering grammar}, where the developer merely needs to provide a set of lexical items particular to the language. As a substitute for the aligned corpus, we also consider a scenario where one only has the spoken side, and the corresponding written side is "hallucinated" by composing the spoken side with the inverted normalization grammar. We investigate the accuracy of a text normalization engine under each of these scenarios. We report the results of experiments on English and Russian.

##### Abstract (translated by Google)
在诸如文本到语音（TTS）或自动语音识别（ASR）的语音应用中，\ emph {文本标准化}是指从\ emph {写入}表示转换为文本如何表示是\ emph {发音}。在所有现实世界的语音应用中，文本规范化引擎大部分是由手工开发的。例如，可以使用手工建立的语法来枚举给定语言中给定标记的可能方式，以及用于在上下文中选择最合适发音的统计模型。在这项研究中，我们考察了在文本规范化引擎中使用或多或少语言特定领域知识的折衷。在大多数数据丰富的情况下，我们可以访问一个精心构造的手工构建的规范化语法，对于任何给定的标记都会为该标记产生一组所有可能的语言表达。我们还假设一个统一的书面口头发言的语料库，从中我们可以训练一个排名模型，选择适当的语境在给定的情况下。作为精心构建的语法的替代，我们还考虑一种具有语言通用规范化的方案，其中开发人员只需要提供一组特定于语言的词汇项。作为对齐的语料库的替代，我们也考虑一个只有口语的情景，相应的写作方面是通过用倒置的规范化语法构成口语方面来“幻觉”的。我们调查了每种情况下文本规范化引擎的准确性。我们报告英语和俄语的实验结果。

##### URL
[https://arxiv.org/abs/1609.06649](https://arxiv.org/abs/1609.06649)

##### PDF
[https://arxiv.org/pdf/1609.06649](https://arxiv.org/pdf/1609.06649)

