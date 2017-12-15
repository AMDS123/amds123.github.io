---
layout: post
title: "Role of Morphology Injection in Statistical Machine Translation"
date: 2017-09-16 09:40:36
categories: arXiv_CL
tags: arXiv_CL Sparse Face
author: Sreelekha S, Pushpak Bhattacharyya
mathjax: true
---

* content
{:toc}

##### Abstract
Phrase-based Statistical models are more commonly used as they perform optimally in terms of both, translation quality and complexity of the system. Hindi and in general all Indian languages are morphologically richer than English. Hence, even though Phrase-based systems perform very well for the less divergent language pairs, for English to Indian language translation, we need more linguistic information (such as morphology, parse tree, parts of speech tags, etc.) on the source side. Factored models seem to be useful in this case, as Factored models consider word as a vector of factors. These factors can contain any information about the surface word and use it while translating. Hence, the objective of this work is to handle morphological inflections in Hindi and Marathi using Factored translation models while translating from English. SMT approaches face the problem of data sparsity while translating into a morphologically rich language. It is very unlikely for a parallel corpus to contain all morphological forms of words. We propose a solution to generate these unseen morphological forms and inject them into original training corpora. In this paper, we study factored models and the problem of sparseness in context of translation to morphologically rich languages. We propose a simple and effective solution which is based on enriching the input with various morphological forms of words. We observe that morphology injection improves the quality of translation in terms of both adequacy and fluency. We verify this with the experiments on two morphologically rich languages: Hindi and Marathi, while translating from English.

##### Abstract (translated by Google)
基于短语的统计模型更常用，因为它们在翻译质量和系统复杂性方面表现最佳。印地语和一般所有印度语言在形态上比英语丰富。因此，即使基于短语的系统对于较少发散的语言对表现得非常好，但对于英语到印度语的翻译，我们还需要更多源语言的语言信息（例如形态学，语法分析树，词性标记等） 。 Factored模型似乎在这种情况下是有用的，因为Factored模型认为单词是因素的一个向量。这些因素可以包含关于表面词的任何信息，并在翻译时使用它。因此，这项工作的目的是处理印地语和马拉地语的形态变化，使用Factored翻译模型，同时从英语翻译。 SMT方法面临数据稀疏的问题，同时转化为形态丰富的语言。平行语料库不太可能包含所有词形的形式。我们提出了一个解决方案来产生这些看不见的形态形式，并将其注入原始训练语料库。在这篇论文中，我们研究了在形式丰富的语言翻译的语境中的分解模型和稀疏性问题。我们提出一个简单而有效的解决方案，它基于丰富词汇的各种形态形式的输入。我们观察到，形态注入在充足性和流畅性方面提高了翻译的质量。我们用两种形态丰富的语言进行了实验：印地语和马拉地语，同时从英语翻译。

##### URL
[https://arxiv.org/abs/1709.05487](https://arxiv.org/abs/1709.05487)

##### PDF
[https://arxiv.org/pdf/1709.05487](https://arxiv.org/pdf/1709.05487)

