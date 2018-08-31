---
layout: post
title: "Retrieval-Based Neural Code Generation"
date: 2018-08-29 20:01:21
categories: arXiv_CL
tags: arXiv_CL
author: Shirley Anugrah Hayati, Raphael Olivier, Pravalika Avvaru, Pengcheng Yin, Anthony Tomasic, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
In models to generate program source code from natural language, representing this code in a tree structure has been a common approach. However, existing methods often fail to generate complex code correctly due to a lack of ability to memorize large and complex structures. We introduce ReCode, a method based on subtree retrieval that makes it possible to explicitly reference existing code examples within a neural code generation model. First, we retrieve sentences that are similar to input sentences using a dynamic-programming-based sentence similarity scoring method. Next, we extract n-grams of action sequences that build the associated abstract syntax tree. Finally, we increase the probability of actions that cause the retrieved n-gram action subtree to be in the predicted code. We show that our approach improves the performance on two code generation tasks by up to +2.6 BLEU.

##### Abstract (translated by Google)
在从自然语言生成程序源代码的模型中，在树结构中表示此代码是一种常见的方法。但是，由于缺乏记忆大型复杂结构的能力，现有方法通常无法正确生成复杂代码。我们介绍了ReCode，这是一种基于子树检索的方法，可以明确地引用神经代码生成模型中的现有代码示例。首先，我们使用基于动态编程的句子相似性评分方法检索与输入句子类似的句子。接下来，我们提取构建相关抽象语法树的n-gram动作序列。最后，我们增加了导致检索到的n-gram动作子树在预测代码中的动作的概率。我们表明，我们的方法可以将两个代码生成任务的性能提高到+2.6 BLEU。

##### URL
[http://arxiv.org/abs/1808.10025](http://arxiv.org/abs/1808.10025)

##### PDF
[http://arxiv.org/pdf/1808.10025](http://arxiv.org/pdf/1808.10025)

