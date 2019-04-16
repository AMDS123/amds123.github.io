---
layout: post
title: "code2seq: Generating Sequences from Structured Representations of Code"
date: 2019-02-21 14:12:56
categories: arXiv_CL
tags: arXiv_CL Attention Summarization NMT
author: Uri Alon, Shaked Brody, Omer Levy, Eran Yahav
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to generate natural language sequences from source code snippets has a variety of applications such as code summarization, documentation, and retrieval. Sequence-to-sequence (seq2seq) models, adopted from neural machine translation (NMT), have achieved state-of-the-art performance on these tasks by treating source code as a sequence of tokens. We present ${\rm {\scriptsize CODE2SEQ}}$: an alternative approach that leverages the syntactic structure of programming languages to better encode source code. Our model represents a code snippet as the set of compositional paths in its abstract syntax tree (AST) and uses attention to select the relevant paths while decoding. We demonstrate the effectiveness of our approach for two tasks, two programming languages, and four datasets of up to $16$M examples. Our model significantly outperforms previous models that were specifically designed for programming languages, as well as state-of-the-art NMT models. An interactive online demo of our model is available at this http URL. Our code, data and trained models are available at this http URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.01400](https://arxiv.org/abs/1808.01400)

##### PDF
[https://arxiv.org/pdf/1808.01400](https://arxiv.org/pdf/1808.01400)

