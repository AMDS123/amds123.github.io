---
layout: post
title: "Title Generation for Web Tables"
date: 2018-06-30 00:57:15
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Braden Hancock, Hongrae Lee, Cong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Descriptive titles provide crucial context for interpreting tables that are extracted from web pages and are a key component of table-based web applications. Prior approaches have attempted to produce titles by selecting existing text snippets associated with the table. These approaches, however, are limited by their dependence on suitable titles existing a priori. In our user study, we observe that the relevant information for the title tends to be scattered across the page, and often---more than 80% of time---does not appear verbatim anywhere in the page. We propose instead the application of a sequence-to-sequence neural network model as a more generalizable means of generating high-quality titles. This is accomplished by extracting many text snippets that have potentially relevant information to the table, encoding them into an input sequence, and using both copy and generation mechanisms in the decoder to balance relevance and readability of the generated title. We validate this approach with human evaluation on sample web tables and report that while sequence models with only a copy mechanism or only a generation mechanism are easily outperformed by simple selection-based baselines, the model with both capabilities outperforms them all, approaching the quality of crowdsourced titles while training on fewer than ten thousand examples. To the best of our knowledge, the proposed technique is the first to consider text-generation methods for table titles, and establishes a new state of the art.

##### Abstract (translated by Google)
描述性标题为解释从网页中提取的表格提供了至关重要的上下文，并且是基于表格的Web应用程序的关键组件。先前的方法已经尝试通过选择与表相关联的现有文本片段来产生标题。然而，这些方法受到它们对先验存在的合适标题的依赖的限制。在我们的用户研究中，我们发现标题的相关信息往往分散在整个页面中，并且通常---超过80％的时间---在页面的任何地方都不会逐字显示。相反，我们建议应用序列到序列神经网络模型作为生成高质量标题的更通用的方法。这是通过向表中提取具有潜在相关信息的许多文本片段，将它们编码为输入序列，以及在解码器中使用复制和生成机制来平衡生成的标题的相关性和可读性来实现的。我们通过对样本网表进行人工评估验证了这种方法，并报告说，虽然只有复制机制或仅生成机制的序列模型很容易通过简单的基于选择的基线来表现，但具有这两种能力的模型都优于所有模型，接近质量众包标题，而培训不到一万个例子。据我们所知，所提出的技术是第一个考虑表标题的文本生成方法，并建立了一种新的技术水平。

##### URL
[http://arxiv.org/abs/1807.00099](http://arxiv.org/abs/1807.00099)

##### PDF
[http://arxiv.org/pdf/1807.00099](http://arxiv.org/pdf/1807.00099)

