---
layout: post
title: "code2seq: Generating Sequences from Structured Representations of Code"
date: 2018-08-04 01:26:07
categories: arXiv_AI
tags: arXiv_AI Attention Summarization NMT
author: Uri Alon, Omer Levy, Eran Yahav
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to generate natural language sequences from source code snippets can be used for code summarization, documentation, and retrieval. Sequence-to-sequence (seq2seq) models, adopted from neural machine translation (NMT), have achieved state-of-the-art performance on these tasks by treating source code as a sequence of tokens. We present ${\rm {\scriptsize CODE2SEQ}}$: an alternative approach that leverages the syntactic structure of programming languages to better encode source code. Our model represents a code snippet as the set of paths in its abstract syntax tree (AST) and uses attention to select the relevant paths during decoding, much like contemporary NMT models. We demonstrate the effectiveness of our approach for two tasks, two programming languages, and four datasets of up to 16M examples. Our model significantly outperforms previous models that were specifically designed for programming languages, as well as general state-of-the-art NMT models.

##### Abstract (translated by Google)
从源代码片段生成自然语言序列的功能可用于代码汇总，文档和检索。从神经机器翻译（NMT）采用的序列到序列（seq2seq）模型通过将源代码视为一系列令牌，已经在这些任务上实现了最先进的性能。我们提出$ {\ rm {\ scriptsize CODE2SEQ}} $：一种利用编程语言的句法结构来更好地编码源代码的替代方法。我们的模型将代码片段表示为其抽象语法树（AST）中的路径集，并使用注意力在解码期间选择相关路径，就像当代NMT模型一样。我们展示了我们的方法对两个任务，两种编程语言和四个最多16M示例的数据集的有效性。我们的模型明显优于以前为编程语言专门设计的模型，以及一般的最先进的NMT模型。

##### URL
[https://arxiv.org/abs/1808.01400](https://arxiv.org/abs/1808.01400)

##### PDF
[https://arxiv.org/pdf/1808.01400](https://arxiv.org/pdf/1808.01400)

