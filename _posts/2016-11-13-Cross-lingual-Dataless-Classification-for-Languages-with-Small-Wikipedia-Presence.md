---
layout: post
title: "Cross-lingual Dataless Classification for Languages with Small Wikipedia Presence"
date: 2016-11-13 12:20:33
categories: arXiv_CL
tags: arXiv_CL Classification
author: Yangqiu Song, Stephen Mayhew, Dan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an approach to classify documents in any language into an English topical label space, without any text categorization training data. The approach, Cross-Lingual Dataless Document Classification (CLDDC) relies on mapping the English labels or short category description into a Wikipedia-based semantic representation, and on the use of the target language Wikipedia. Consequently, performance could suffer when Wikipedia in the target language is small. In this paper, we focus on languages with small Wikipedias, (Small-Wikipedia languages, SWLs). We use a word-level dictionary to convert documents in a SWL to a large-Wikipedia language (LWLs), and then perform CLDDC based on the LWL's Wikipedia. This approach can be applied to thousands of languages, which can be contrasted with machine translation, which is a supervision heavy approach and can be done for about 100 languages. We also develop a ranking algorithm that makes use of language similarity metrics to automatically select a good LWL, and show that this significantly improves classification of SWLs' documents, performing comparably to the best bridge possible.

##### Abstract (translated by Google)
本文提出了一种将任何语言的文档分类到英文主题标签空间的方法，没有任何文本分类训练数据。跨语言无数据文档分类（CLDDC）方法依赖于将英文标签或简短类别描述映射到基于维基百科的语义表示以及使用目标语言维基百科。因此，当目标语言的维基百科很小时，性能可能会受到影响。在本文中，我们重点关注具有小维基百科的语言（小维基百科语言，SWLs）。我们使用字级字典将SWL中的文档转换为大维基百科语言（LWL），然后基于LWL的Wikipedia执行CLDDC。这种方法可以应用于数以千计的语言，这可以与机器翻译形成对比，这是一种监督繁重的方法，可以为大约100种语言完成。我们还开发了一种排序算法，利用语言相似性度量来自动选择一个好的LWL，并显示这显着改善了SWLs文档的分类，与可能的最佳桥接类似。

##### URL
[https://arxiv.org/abs/1611.04122](https://arxiv.org/abs/1611.04122)

##### PDF
[https://arxiv.org/pdf/1611.04122](https://arxiv.org/pdf/1611.04122)

