---
layout: post
title: "Memoisation: Purely, Left-recursively, and with Style"
date: 2017-07-15 11:03:49
categories: arXiv_CL
tags: arXiv_CL Face
author: Samer Abdallah
mathjax: true
---

* content
{:toc}

##### Abstract
Memoisation, or tabling, is a well-known technique that yields large improvements in the performance of some recursive computations. Tabled resolution in Prologs such as XSB and B-Prolog can transform so called left-recursive predicates from non-terminating computations into finite and well-behaved ones. In the functional programming literature, memoisation has usually been implemented in a way that does not handle left-recursion, requiring supplementary mechanisms to prevent non-termination. A notable exception is Johnson's (1995) continuation passing approach in Scheme. This, however, relies on mutation of a memo table data structure and coding in explicit continuation passing style. We show how Johnson's approach can be implemented purely functionally in a modern, strongly typed functional language (OCaml), presented via a monadic interface that hides the implementation details, yet providing a way to return a compact represention of the memo tables at the end of the computation.

##### Abstract (translated by Google)
记忆或制表是一种众所周知的技术，可以大大提高一些递归计算的性能。在诸如XSB和B-Prolog之类的Prolog中的表格解析可以将所谓的左递归谓词从非终止计算转换成有限的和行为良好的计算。在功能性编程文献中，通常以不能处理左递归的方式实现记忆，需要辅助机制来防止不终止。约翰逊（1995）在计划中延续传球的方法是一个明显的例外。但是，这依赖于备忘表数据结构的变化以及显式延续传递风格的编码。我们展示了约翰逊的方法如何在一个现代的强类型函数语言（OCaml）中纯粹的功能实现，通过隐藏实现细节的monadic接口来呈现，但是提供了一种方法来返回紧凑的备忘录表示方式计算。

##### URL
[https://arxiv.org/abs/1707.04724](https://arxiv.org/abs/1707.04724)

##### PDF
[https://arxiv.org/pdf/1707.04724](https://arxiv.org/pdf/1707.04724)

