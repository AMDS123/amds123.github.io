---
layout: post
title: "An Operator for Entity Extraction in MapReduce"
date: 2015-12-15 21:23:20
categories: arXiv_CL
tags: arXiv_CL
author: Ndapandula Nakashole
mathjax: true
---

* content
{:toc}

##### Abstract
Dictionary-based entity extraction involves finding mentions of dictionary entities in text. Text mentions are often noisy, containing spurious or missing words. Efficient algorithms for detecting approximate entity mentions follow one of two general techniques. The first approach is to build an index on the entities and perform index lookups of document substrings. The second approach recognizes that the number of substrings generated from documents can explode to large numbers, to get around this, they use a filter to prune many such substrings which do not match any dictionary entity and then only verify the remaining substrings if they are entity mentions of dictionary entities, by means of a text join. The choice between the index-based approach and the filter & verification-based approach is a case-to-case decision as the best approach depends on the characteristics of the input entity dictionary, for example frequency of entity mentions. Choosing the right approach for the setting can make a substantial difference in execution time. Making this choice is however non-trivial as there are parameters within each of the approaches that make the space of possible approaches very large. In this paper, we present a cost-based operator for making the choice among execution plans for entity extraction. Since we need to deal with large dictionaries and even larger large datasets, our operator is developed for implementations of MapReduce distributed algorithms.

##### Abstract (translated by Google)
基于字典的实体提取涉及在文本中查找字典实体的提及。文字提到往往是嘈杂的，包含虚假或遗漏的话。用于检测近似实体提及的有效算法遵循两种通用技术中的一种。第一种方法是在实体上建立一个索引并执行文档子字符串的索引查找。第二种方法认识到，从文档生成的子字符串的数量可以大量爆炸，为了解决这个问题，他们使用过滤器来修剪许多这样的不匹配任何字典实体的子字符串，然后只验证其余的子字符串，如果它们是实体通过文本连接来提及字典实体。基于索引的方法和基于过滤器和基于验证的方法之间的选择是个案到个案的决定，因为最好的方法取决于输入实体字典的特征，例如实体提到的频率。选择正确的设置方法可以在执行时间上产生实质性的差异。然而，做出这样的选择是非常重要的，因为每种方法都有一些参数，使得可能方法的空间非常大。在本文中，我们提出了一个基于成本的操作符，用于在实体提取的执行计划中进行选择。由于我们需要处理大字典和更大的大数据集，所以我们的操作符是为了实现MapReduce分布式算法而开发的。

##### URL
[https://arxiv.org/abs/1512.04973](https://arxiv.org/abs/1512.04973)

##### PDF
[https://arxiv.org/pdf/1512.04973](https://arxiv.org/pdf/1512.04973)

