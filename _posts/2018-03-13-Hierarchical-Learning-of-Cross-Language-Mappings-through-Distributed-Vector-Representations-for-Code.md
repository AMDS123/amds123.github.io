---
layout: post
title: "Hierarchical Learning of Cross-Language Mappings through Distributed Vector Representations for Code"
date: 2018-03-13 10:30:55
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Nghi D. Q. Bui, Lingxiao Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Translating a program written in one programming language to another can be useful for software development tasks that need functionality implementations in different languages. Although past studies have considered this problem, they may be either specific to the language grammars, or specific to certain kinds of code elements (e.g., tokens, phrases, API uses). This paper proposes a new approach to automatically learn cross-language representations for various kinds of structural code elements that may be used for program translation. Our key idea is two folded: First, we normalize and enrich code token streams with additional structural and semantic information, and train cross-language vector representations for the tokens (a.k.a. shared embeddings based on word2vec, a neural-network-based technique for producing word embeddings; Second, hierarchically from bottom up, we construct shared embeddings for code elements of higher levels of granularity (e.g., expressions, statements, methods) from the embeddings for their constituents, and then build mappings among code elements across languages based on similarities among embeddings. 
 Our preliminary evaluations on about 40,000 Java and C# source files from 9 software projects show that our approach can automatically learn shared embeddings for various code elements in different languages and identify their cross-language mappings with reasonable Mean Average Precision scores. When compared with an existing tool for mapping library API methods, our approach identifies many more mappings accurately. The mapping results and code can be accessed at https://github.com/bdqnghi/hierarchical-programming-language-mapping. We believe that our idea for learning cross-language vector representations with code structural information can be a useful step towards automated program translation.

##### Abstract (translated by Google)
将用一种编程语言编写的程序翻译为另一种编程语言可能对需要使用不同语言的功能实现的软件开发任务有用。虽然过去的研究已经考虑过这个问题，但它们可能是特定于语言语法的，或者特定于某些类型的代码元素（例如，令牌，短语，API使用）。本文提出了一种自动学习可用于程序转换的各种结构代码元素的跨语言表示的新方法。我们的主要思想是两个折叠：首先，我们使用额外的结构和语义信息来标准化和丰富代码标记流，并且为令牌训练跨语言向量表示（也称为基于word2vec的共享嵌入，一种基于神经网络的生成技术词嵌入;其次，从底层开始，我们从其成分的嵌入中为粒度更高的代码元素（例如，表达式，语句，方法）构建共享嵌入，然后基于相似性在跨语言的代码元素之间构建映射在嵌入之中。
 我们对来自9个软件项目的约40,000个Java和C＃源文件进行了初步评估，结果表明我们的方法可以自动学习不同语言的各种代码元素的共享嵌入，并通过合理的平均精度分数来识别其跨语言映射。与现有的映射库API方法的工具相比，我们的方法可以准确地识别更多的映射。映射结果和代码可以访问https://github.com/bdqnghi/hierarchical-programming-language-mapping。我们相信，我们使用代码结构信息学习跨语言向量表示的想法可能是实现自动化程序转换的有用步骤。

##### URL
[http://arxiv.org/abs/1803.04715](http://arxiv.org/abs/1803.04715)

##### PDF
[http://arxiv.org/pdf/1803.04715](http://arxiv.org/pdf/1803.04715)

