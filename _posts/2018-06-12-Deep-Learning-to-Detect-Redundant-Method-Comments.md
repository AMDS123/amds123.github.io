---
layout: post
title: "Deep Learning to Detect Redundant Method Comments"
date: 2018-06-12 15:49:14
categories: arXiv_CL
tags: arXiv_CL Deep_Learning Language_Model Quantitative
author: Annie Louis, Santanu Kumar Dash, Earl T. Barr, Charles Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Comments in software are critical for maintenance and reuse. But apart from prescriptive advice, there is little practical support or quantitative understanding of what makes a comment useful. In this paper, we introduce the task of identifying comments which are uninformative about the code they are meant to document. To address this problem, we introduce the notion of comment entailment from code, high entailment indicating that a comment's natural language semantics can be inferred directly from the code. Although not all entailed comments are low quality, comments that are too easily inferred, for example, comments that restate the code, are widely discouraged by authorities on software style. Based on this, we develop a tool called CRAIC which scores method-level comments for redundancy. Highly redundant comments can then be expanded or alternately removed by the developer. CRAIC uses deep language models to exploit large software corpora without requiring expensive manual annotations of entailment. We show that CRAIC can perform the comment entailment task with good agreement with human judgements. Our findings also have implications for documentation tools. For example, we find that common tags in Javadoc are at least two times more predictable from code than non-Javadoc sentences, suggesting that Javadoc tags are less informative than more free-form comments

##### Abstract (translated by Google)
软件中的评论对维护和重用至关重要。但除了规定性建议之外，对评论有用的内容几乎没有实际支持或量化理解。在本文中，我们介绍识别意见的任务，这些意见对他们要记录的代码没有意义。为了解决这个问题，我们引入了来自代码的评论蕴含的概念，高含量表明评论的自然语言语义可以直接从代码中推断出来。虽然并不是所有的评论都是低质量的，但是很容易被推断出来的评论，例如重申代码的评论，在软件风格方面受到了当局的广泛阻碍。基于此，我们开发了一种名为CRAIC的工具，对冗余度进行方法级评论。高度多余的评论可以由开发者扩展或交替删除。 CRAIC使用深层语言模型来开发大型软件语料库，而不需要昂贵的手册注释。我们表明，CRAIC可以与人类判断很好地达成评论意图任务。我们的发现也对文档工具有影响。例如，我们发现Javadoc中的通用标签至少比非Javadoc语句的代码可预测性要高出两倍，这表明Javadoc标签的信息量低于更多自由格式的评论

##### URL
[http://arxiv.org/abs/1806.04616](http://arxiv.org/abs/1806.04616)

##### PDF
[http://arxiv.org/pdf/1806.04616](http://arxiv.org/pdf/1806.04616)

