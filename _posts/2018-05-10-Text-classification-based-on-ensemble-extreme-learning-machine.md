---
layout: post
title: "Text classification based on ensemble extreme learning machine"
date: 2018-05-10 06:10:46
categories: arXiv_AI
tags: arXiv_AI Sparse Text_Classification Classification
author: Ming Li, Peilun Xiao, Ju Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel approach based on cost-sensitive ensemble weighted extreme learning machine; we call this approach AE1-WELM. We apply this approach to text classification. AE1-WELM is an algorithm including balanced and imbalanced multiclassification for text classification. Weighted ELM assigning the different weights to the different samples improves the classification accuracy to a certain extent, but weighted ELM considers the differences between samples in the different categories only and ignores the differences between samples within the same categories. We measure the importance of the documents by the sample information entropy, and generate cost-sensitive matrix and factor based on the document importance, then embed the cost-sensitive weighted ELM into the AdaBoost.M1 framework seamlessly. Vector space model(VSM) text representation produces the high dimensions and sparse features which increase the burden of ELM. To overcome this problem, we develop a text classification framework combining the word vector and AE1-WELM. The experimental results show that our method provides an accurate, reliable and effective solution for text classification.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于成本敏感的集合加权极限学习机的新方法;我们称这种方法为AE1-WELM。我们将这种方法应用于文本分类。 AE1-WELM是一种针对文本分类的包含平衡和不平衡多分类的算法。加权ELM将不同权重分配给不同样本在一定程度上改善了分类准确性，但加权ELM仅考虑了不同类别中样本之间的差异并且忽略了相同类别内的样本之间的差异。我们通过样本信息熵来度量文档的重要性，并根据文档重要性生成对成本敏感的矩阵和因子，然后将成本敏感的加权ELM无缝地嵌入到AdaBoost.M1框架中。向量空间模型（VSM）文本表示产生高维和稀疏特征，这增加了ELM的负担。为了克服这个问题，我们开发了一个文字分类框架，将矢量和AE1-WELM相结合。实验结果表明，我们的方法为文本分类提供了准确，可靠和有效的解决方案。

##### URL
[http://arxiv.org/abs/1805.06525](http://arxiv.org/abs/1805.06525)

##### PDF
[http://arxiv.org/pdf/1805.06525](http://arxiv.org/pdf/1805.06525)

