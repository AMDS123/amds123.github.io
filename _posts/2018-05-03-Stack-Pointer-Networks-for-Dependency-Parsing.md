---
layout: post
title: "Stack-Pointer Networks for Dependency Parsing"
date: 2018-05-03 02:23:28
categories: arXiv_CV
tags: arXiv_CV
author: Xuezhe Ma, Zecong Hu, Jingzhou Liu, Nanyun Peng, Graham Neubig, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel architecture for dependency parsing: \emph{stack-pointer networks} (\textbf{\textsc{StackPtr}}). Combining pointer networks~\citep{vinyals2015pointer} with an internal stack, the proposed model first reads and encodes the whole sentence, then builds the dependency tree top-down (from root-to-leaf) in a depth-first fashion. The stack tracks the status of the depth-first search and the pointer networks select one child for the word at the top of the stack at each step. The \textsc{StackPtr} parser benefits from the information of the whole sentence and all previously derived subtree structures, and removes the left-to-right restriction in classical transition-based parsers. Yet, the number of steps for building any (including non-projective) parse tree is linear in the length of the sentence just as other transition-based parsers, yielding an efficient decoding algorithm with $O(n^2)$ time complexity. We evaluate our model on 29 treebanks spanning 20 languages and different dependency annotation schemas, and achieve state-of-the-art performance on 21 of them.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.01087](https://arxiv.org/abs/1805.01087)

##### PDF
[https://arxiv.org/pdf/1805.01087](https://arxiv.org/pdf/1805.01087)

