---
layout: post
title: "A Constraint Network Based Approach to Memory Layout Optimization"
date: 2007-10-25 11:59:01
categories: arXiv_CV
tags: arXiv_CV Optimization
author: G. Chen, M. Kandemir, M. Karakoy
mathjax: true
---

* content
{:toc}

##### Abstract
While loop restructuring based code optimization for array intensive applications has been successful in the past, it has several problems such as the requirement of checking dependences (legality issues) and transformation of all of the array references within the loop body indiscriminately (while some of the references can benefit from the transformation, others may not). As a result, data transformations, i.e., transformations that modify memory layout of array data instead of loop structure have been proposed. One of the problems associated with data transformations is the difficulty of selecting a memory layout for an array that is acceptable to the entire program (not just to a single loop). In this paper, we formulate the problem of determining the memory layouts of arrays as a constraint network, and explore several methods of solution in a systematic way. Our experiments provide strong support in favor of employing constraint processing, and point out future research directions.

##### Abstract (translated by Google)
基于循环重构的阵列密集型应用程序代码优化过去已经取得了成功，但也存在一些问题，比如检查依赖性（合法性问题）的要求和循环体内所有数组引用的转换（而一些引用可以从转换中受益，其他可能不会）。结果，已经提出了数据变换，即，修改阵列数据的存储器布局而不是循环结构的变换。与数据转换相关的一个问题是难以为整个程序选择一个数组的内存布局（而不仅仅是单个循环）。在本文中，我们制定了确定阵列作为约束网络的存储器布局的问题，并且系统地探索了几种解决方法。我们的实验为利用约束处理提供了强有力的支持，并指出了未来的研究方向。

##### URL
[https://arxiv.org/abs/0710.4807](https://arxiv.org/abs/0710.4807)

##### PDF
[https://arxiv.org/pdf/0710.4807](https://arxiv.org/pdf/0710.4807)

