---
layout: post
title: "Compilation as a Typed EDSL-to-EDSL Transformation"
date: 2016-04-05 09:58:06
categories: arXiv_SD
tags: arXiv_SD
author: Emil Axelsson
mathjax: true
---

* content
{:toc}

##### Abstract
This article is about an implementation and compilation technique that is used in RAW-Feldspar which is a complete rewrite of the Feldspar embedded domain-specific language (EDSL) (Axelsson et al. 2010). Feldspar is high-level functional language that generates efficient C code to run on embedded targets. The gist of the technique presented in this post is the following: rather writing a back end that converts pure Feldspar expressions directly to C, we translate them to a low-level monadic EDSL. From the low-level EDSL, C code is then generated. This approach has several advantages: 1. The translation is simpler to write than a complete C back end. 2. The translation is between two typed EDSLs, which rules out many potential errors. 3. The low-level EDSL is reusable and can be shared between several high-level EDSLs. Although the article contains a lot of code, most of it is in fact reusable. As mentioned in Discussion, we can write the same implementation in less than 50 lines of code using generic libraries that we have developed to support Feldspar.

##### Abstract (translated by Google)
这篇文章是关于在RAW-Feldspar中使用的实现和编译技术，它是对长石嵌入式领域特定语言（EDSL）的完全重写（Axelsson et al。2010）。长石是高级功能语言，可生成高效的C代码以在嵌入式目标上运行。在这篇文章中提到的技术的要点如下：写一个后端，将纯长石表达式直接转换为C，我们将其转换为低级一元EDSL。然后从低级别的EDSL生成C代码。这种方法有几个优点：1.翻译比完整的C后端更容易编写。 2.翻译是在两种类型的EDSL之间，排除了许多潜在的错误。 3.低级EDSL可重用，可以在多个高级EDSL之间共享。尽管文章中包含很多代码，但其中大部分实际上都是可重用的。正如讨论中提到的，我们可以使用我们开发的用于支持Feldspar的通用库，在少于50行的代码中编写相同的实现。

##### URL
[https://arxiv.org/abs/1603.08865](https://arxiv.org/abs/1603.08865)

##### PDF
[https://arxiv.org/html/1603.08865](https://arxiv.org/html/1603.08865)

