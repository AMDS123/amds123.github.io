---
layout: post
title: "Data Cleaning for XML Electronic Dictionaries via Statistical Anomaly Detection"
date: 2016-04-11 04:01:43
categories: arXiv_SD
tags: arXiv_SD Language_Model Detection Recognition
author: Michael Bloodgood, Benjamin Strauss
mathjax: true
---

* content
{:toc}

##### Abstract
Many important forms of data are stored digitally in XML format. Errors can occur in the textual content of the data in the fields of the XML. Fixing these errors manually is time-consuming and expensive, especially for large amounts of data. There is increasing interest in the research, development, and use of automated techniques for assisting with data cleaning. Electronic dictionaries are an important form of data frequently stored in XML format that frequently have errors introduced through a mixture of manual typographical entry errors and optical character recognition errors. In this paper we describe methods for flagging statistical anomalies as likely errors in electronic dictionaries stored in XML format. We describe six systems based on different sources of information. The systems detect errors using various signals in the data including uncommon characters, text length, character-based language models, word-based language models, tied-field length ratios, and tied-field transliteration models. Four of the systems detect errors based on expectations automatically inferred from content within elements of a single field type. We call these single-field systems. Two of the systems detect errors based on correspondence expectations automatically inferred from content within elements of multiple related field types. We call these tied-field systems. For each system, we provide an intuitive analysis of the type of error that it is successful at detecting. Finally, we describe two larger-scale evaluations using crowdsourcing with Amazon's Mechanical Turk platform and using the annotations of a domain expert. The evaluations consistently show that the systems are useful for improving the efficiency with which errors in XML electronic dictionaries can be detected.

##### Abstract (translated by Google)
许多重要的数据形式都以XML格式进行数字存储。 XML的字段中的数据的文本内容中可能出现错误。手动修复这些错误是非常耗时和昂贵的，特别是对于大量的数据。人们越来越关心自动化技术的研究，开发和使用，以帮助数据清理。电子字典是经常以XML格式存储的数据的重要形式，其经常通过混合手工印刷输入错误和光学字符识别错误而引入错误。在本文中，我们描述了将统计异常标记为XML格式存储的电子词典中可能的错误的方法。我们根据不同的信息来源描述了六个系统。系统使用数据中的各种信号检测错误，包括不常见字符，文本长度，基于字符的语言模型，基于字的语言模型，绑定字段长度比率和绑定字段音译模型。其中四个系统根据预期从单个字段类型的元素内容自动推断出错误。我们称这些单场系统。其中两个系统根据对应性预期来检测错误，该对应性预期从多个相关字段类型的元素内的内容自动推断。我们称这些绑定的系统。对于每个系统，我们提供了一个直观的分析错误的类型，它是成功的检测。最后，我们用Amazon的Mechanical Turk平台使用众包来描述两个大规模的评估，并使用领域专家的注释。评估一致表明，这些系统对于提高XML电子字典中的错误的检测效率是有用的。

##### URL
[https://arxiv.org/abs/1602.07807](https://arxiv.org/abs/1602.07807)

##### PDF
[https://arxiv.org/pdf/1602.07807](https://arxiv.org/pdf/1602.07807)

