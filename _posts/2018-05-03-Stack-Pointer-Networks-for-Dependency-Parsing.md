---
layout: post
title: "Stack-Pointer Networks for Dependency Parsing"
date: 2018-05-03 02:23:28
categories: arXiv_CL
tags: arXiv_CL
author: Xuezhe Ma, Zecong Hu, Jingzhou Liu, Nanyun Peng, Graham Neubig, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel architecture for dependency parsing: \emph{stack-pointer networks} (\textbf{\textsc{StackPtr}}). Combining pointer networks~\citep{vinyals2015pointer} with an internal stack, the proposed model first reads and encodes the whole sentence, then builds the dependency tree top-down (from root-to-leaf) in a depth-first fashion. The stack tracks the status of the depth-first search and the pointer networks select one child for the word at the top of the stack at each step. The \textsc{StackPtr} parser benefits from the information of the whole sentence and all previously derived subtree structures, and removes the left-to-right restriction in classical transition-based parsers. Yet, the number of steps for building any (including non-projective) parse tree is linear in the length of the sentence just as other transition-based parsers, yielding an efficient decoding algorithm with $O(n^2)$ time complexity. We evaluate our model on 29 treebanks spanning 20 languages and different dependency annotation schemas, and achieve state-of-the-art performance on 21 of them.

##### Abstract (translated by Google)
我们介绍了一种新颖的依赖解析体系结构：\ emph {stack-pointer networks}（\ textbf {\ textsc {StackPtr}}）。将指针网络〜\ citep {vinyals2015pointer}与内部堆栈相结合，所提出的模型首先读取并编码整个句子，然后以深度优先的方式自上而下（从根到叶）构建依赖树。堆栈跟踪深度优先搜索的状态，并且指针网络在每个步骤为堆栈顶部的单词选择一个孩子。 \ textsc {StackPtr}解析器受益于整个句子和所有以前派生的子树结构的信息，并在经典的基于转换的解析器中消除了从左到右的限制。然而，与其他基于转换的解析器一样，构建任何（包括非射影）解析树的步骤的数量在句子的长度上是线性的，这产生了具有$ O（n ^ 2）$时间复杂度的高效解码算法。我们在跨越20种语言和不同依赖性注释模式的29个树库上评估我们的模型，并在其中21个上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1805.01087](http://arxiv.org/abs/1805.01087)

##### PDF
[http://arxiv.org/pdf/1805.01087](http://arxiv.org/pdf/1805.01087)

