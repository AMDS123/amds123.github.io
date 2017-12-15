---
layout: post
title: "Detecting Table Region in PDF Documents Using Distant Supervision"
date: 2015-09-22 17:53:05
categories: arXiv_CV
tags: arXiv_CV Detection Recognition
author: Miao Fan, Doo Soon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Superior to state-of-the-art approaches which compete in table recognition with 67 annotated government reports in PDF format released by {\it ICDAR 2013 Table Competition}, this paper contributes a novel paradigm leveraging large-scale unlabeled PDF documents to open-domain table detection. We integrate the paradigm into our latest developed system ({\it PdfExtra}) to detect the region of tables by means of 9,466 academic articles from the entire repository of {\it ACL Anthology}, where almost all papers are archived by PDF format without annotation for tables. The paradigm first designs heuristics to automatically construct weakly labeled data. It then feeds diverse evidences, such as layouts of documents and linguistic features, which are extracted by {\it Apache PDFBox} and processed by {\it Stanford NLP} toolkit, into different canonical classifiers. We finally use these classifiers, i.e. {\it Naive Bayes}, {\it Logistic Regression} and {\it Support Vector Machine}, to collaboratively vote on the region of tables. Experimental results show that {\it PdfExtra} achieves a great leap forward, compared with the state-of-the-art approach. Moreover, we discuss the factors of different features, learning models and even domains of documents that may impact the performance. Extensive evaluations demonstrate that our paradigm is compatible enough to leverage various features and learning models for open-domain table region detection within PDF files.

##### Abstract (translated by Google)
本文提出了一种利用大规模无标签PDF文档向开放式数据库提供新颖的范例，它优于最先进的方法，在表格识别中竞争67个PDF格式的带注释的政府报告，域表检测。我们将这个范例整合到我们最新开发的系统（{\ it PdfExtra}）中，通过{\ it ACL Anthology}整个库中的9466篇学术文章来检测表格的区域，几乎所有的论文都以PDF格式存档表的注释。该范式首先设计启发式方法来自动构造弱标记的数据。然后将不同的证据（如由{\ it Apache PDFBox}提取并由{\ it Stanford NLP}工具包处理的文档布局和语言特征）输入到不同的规范分类器中。我们最终使用这些分类器，即{\}朴素贝叶斯，{\它逻辑回归}和{\它支持向量机}，合作投票表区域。实验结果表明，相比最先进的方法，{\ PdfExtra}实现了一个巨大的飞跃。此外，我们讨论可能影响绩效的不同特征，学习模式甚至文档领域的因素。广泛的评估表明，我们的范例足够兼容，可以利用各种功能和学习模型在PDF文件中进行开放域表区域检测。

##### URL
[https://arxiv.org/abs/1506.08891](https://arxiv.org/abs/1506.08891)

##### PDF
[https://arxiv.org/pdf/1506.08891](https://arxiv.org/pdf/1506.08891)

