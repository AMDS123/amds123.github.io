---
layout: post
title: "Improving Document Clustering by Eliminating Unnatural Language"
date: 2017-03-17 04:03:36
categories: arXiv_SD
tags: arXiv_SD Classification Detection
author: Myungha Jang, Jinho D. Choi, James Allan
mathjax: true
---

* content
{:toc}

##### Abstract
Technical documents contain a fair amount of unnatural language, such as tables, formulas, pseudo-codes, etc. Unnatural language can be an important factor of confusing existing NLP tools. This paper presents an effective method of distinguishing unnatural language from natural language, and evaluates the impact of unnatural language detection on NLP tasks such as document clustering. We view this problem as an information extraction task and build a multiclass classification model identifying unnatural language components into four categories. First, we create a new annotated corpus by collecting slides and papers in various formats, PPT, PDF, and HTML, where unnatural language components are annotated into four categories. We then explore features available from plain text to build a statistical model that can handle any format as long as it is converted into plain text. Our experiments show that removing unnatural language components gives an absolute improvement in document clustering up to 15%. Our corpus and tool are publicly available.

##### Abstract (translated by Google)
技术文档包含相当数量的非自然语言，如表格，公式，伪代码等。非自然语言可能是混淆现有NLP工具的重要因素。本文提出了一种区分非自然语言和自然语言的有效方法，并评估了非自然语言检测对文档聚类等NLP任务的影响。我们把这个问题看作是一个信息提取任务，并建立一个多类分类模型，将非自然语言组件分为四类。首先，我们通过收集各种格式的幻灯片和论文，PPT，PDF和HTML，创建一个新的注释语料库，其中非自然语言成分被注释为四类。然后，我们探索纯文本提供的功能，建立一个统计模型，可以处理任何格式，只要它被转换成纯文本。我们的实验显示，删除非自然语言组件可以使文档集群中的绝对改进达到15％。我们的语料库和工具是公开的。

##### URL
[https://arxiv.org/abs/1703.05706](https://arxiv.org/abs/1703.05706)

##### PDF
[https://arxiv.org/pdf/1703.05706](https://arxiv.org/pdf/1703.05706)

