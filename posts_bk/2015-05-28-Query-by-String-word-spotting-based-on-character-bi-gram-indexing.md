---
layout: post
title: "Query by String word spotting based on character bi-gram indexing"
date: 2015-05-28 17:59:24
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation
author: Suman K. Ghosh, Ernest Valveny
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a segmentation-free query by string word spotting method. Both the documents and query strings are encoded using a recently proposed word representa- tion that projects images and strings into a common atribute space based on a pyramidal histogram of characters(PHOC). These attribute models are learned using linear SVMs over the Fisher Vector representation of the images along with the PHOC labels of the corresponding strings. In order to search through the whole page, document regions are indexed per character bi- gram using a similar attribute representation. On top of that, we propose an integral image representation of the document using a simplified version of the attribute model for efficient computation. Finally we introduce a re-ranking step in order to boost retrieval performance. We show state-of-the-art results for segmentation-free query by string word spotting in single-writer and multi-writer standard datasets

##### Abstract (translated by Google)
在本文中，我们提出了一种通过字符串字识别方法实现的无分段查询。文档和查询字符串都使用最近提出的字符表示进行编码，该表示将图像和字符串投影到基于金字塔直方图字符（PHOC）的公共属性空间中。这些属性模型是通过使用线性SVM在图像的Fisher Vector表示以及相应的字符串的PHOC标签上学习的。为了搜索整个页面，文档区域使用相似的属性表示法为每个字符节点建立索引。最重要的是，我们使用属性模型的简化版本提出了文档的整体图像表示，以便进行有效的计算。最后我们介绍一个重新排序的步骤，以提高检索性能。我们通过在单写入器和多写入器标准数据集中进行字符串单词识别来显示无分段查询的最新结果

##### URL
[https://arxiv.org/abs/1505.07778](https://arxiv.org/abs/1505.07778)

##### PDF
[https://arxiv.org/pdf/1505.07778](https://arxiv.org/pdf/1505.07778)

