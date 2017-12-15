---
layout: post
title: "Mining Compatible/Incompatible Entities from Question and Answering via Yes/No Answer Classification using Distant Label Expansion"
date: 2016-12-14 06:05:39
categories: arXiv_CL
tags: arXiv_CL Review QA Classification Recognition
author: Hu Xu, Lei Shu, Jingyuan Zhang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Product Community Question Answering (PCQA) provides useful information about products and their features (aspects) that may not be well addressed by product descriptions and reviews. We observe that a product's compatibility issues with other products are frequently discussed in PCQA and such issues are more frequently addressed in accessories, i.e., via a yes/no question "Does this mouse work with windows 10?". In this paper, we address the problem of extracting compatible and incompatible products from yes/no questions in PCQA. This problem can naturally have a two-stage framework: first, we perform Complementary Entity (product) Recognition (CER) on yes/no questions; second, we identify the polarities of yes/no answers to assign the complementary entities a compatibility label (compatible, incompatible or unknown). We leverage an existing unsupervised method for the first stage and a 3-class classifier by combining a distant PU-learning method (learning from positive and unlabeled examples) together with a binary classifier for the second stage. The benefit of using distant PU-learning is that it can help to expand more implicit yes/no answers without using any human annotated data. We conduct experiments on 4 products to show that the proposed method is effective.

##### Abstract (translated by Google)
产品社区问题回答（PCQA）提供有关产品及其功能（方面）的有用信息，可能无法通过产品说明和评论得到很好的解决。我们观察到产品与其他产品的兼容性问题经常在PCQA中讨论，并且这些问题在附件中更频繁地被解决，即通过是/否的问题“这个鼠标是否适用于Windows 10？”。在本文中，我们解决了在PCQA中从“是/否”问题中提取兼容和不兼容产品的问题。这个问题当然可以有两个阶段的框架：第一，我们对是/否问题进行补充实体（产品）认证（CER）;其次，我们确定是/否答案的极性，以指定互补实体兼容性标签（兼容，不兼容或未知）。我们利用现有的第一阶段的无监督方法和三阶段的分类器，结合遥远的PU学习方法（从正面和未标记的例子中学习）和第二阶段的二元分类器。使用遥远的PU学习的好处是，它可以帮助扩大更多隐含的是/否的答案，而不使用任何人类注释的数据。我们对4种产品进行实验，证明所提出的方法是有效的。

##### URL
[https://arxiv.org/abs/1612.04499](https://arxiv.org/abs/1612.04499)

##### PDF
[https://arxiv.org/pdf/1612.04499](https://arxiv.org/pdf/1612.04499)

