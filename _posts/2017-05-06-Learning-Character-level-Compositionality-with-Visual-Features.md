---
layout: post
title: "Learning Character-level Compositionality with Visual Features"
date: 2017-05-06 15:13:24
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding CNN Classification
author: Frederick Liu, Han Lu, Chieh Lo, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work has modeled the compositionality of words by creating character-level models of meaning, reducing problems of sparsity for rare words. However, in many writing systems compositionality has an effect even on the character-level: the meaning of a character is derived by the sum of its parts. In this paper, we model this effect by creating embeddings for characters based on their visual characteristics, creating an image for the character and running it through a convolutional neural network to produce a visual character embedding. Experiments on a text classification task demonstrate that such model allows for better processing of instances with rare characters in languages such as Chinese, Japanese, and Korean. Additionally, qualitative analyses demonstrate that our proposed model learns to focus on the parts of characters that carry semantic content, resulting in embeddings that are coherent in visual space.

##### Abstract (translated by Google)
以前的工作通过创建意义的字符级模型来模拟单词的组成性，减少稀有单词的稀疏性问题。然而，在许多写作系统中，即使在字符级别上，组合性也具有效果：字符的含义是由其部分的总和导出的。在本文中，我们通过根据视觉特征为角色创建嵌入来为这个效果建模，为角色创建一个图像并通过卷积神经网络运行，以产生视觉字符嵌入。对文本分类任务的实验表明，这种模式可以更好地处理中文，日文和韩文等语言中罕见字符的实例。此外，定性分析表明，我们提出的模型学习集中在带有语义内容的字符部分，导致嵌入在视觉空间中是连贯的。

##### URL
[https://arxiv.org/abs/1704.04859](https://arxiv.org/abs/1704.04859)

##### PDF
[https://arxiv.org/pdf/1704.04859](https://arxiv.org/pdf/1704.04859)

