---
layout: post
title: "Large scale biomedical texts classification: a kNN and an ESA-based approaches"
date: 2016-06-09 14:32:50
categories: arXiv_CL
tags: arXiv_CL Knowledge GAN Text_Classification Classification
author: Khadim Dramé (UB), Fleur Mougin (UB), Gayo Diallo (UB)
mathjax: true
---

* content
{:toc}

##### Abstract
With the large and increasing volume of textual data, automated methods for identifying significant topics to classify textual documents have received a growing interest. While many efforts have been made in this direction, it still remains a real challenge. Moreover, the issue is even more complex as full texts are not always freely available. Then, using only partial information to annotate these documents is promising but remains a very ambitious issue. MethodsWe propose two classification methods: a k-nearest neighbours (kNN)-based approach and an explicit semantic analysis (ESA)-based approach. Although the kNN-based approach is widely used in text classification, it needs to be improved to perform well in this specific classification problem which deals with partial information. Compared to existing kNN-based methods, our method uses classical Machine Learning (ML) algorithms for ranking the labels. Additional features are also investigated in order to improve the classifiers' performance. In addition, the combination of several learning algorithms with various techniques for fixing the number of relevant topics is performed. On the other hand, ESA seems promising for this classification task as it yielded interesting results in related issues, such as semantic relatedness computation between texts and text classification. Unlike existing works, which use ESA for enriching the bag-of-words approach with additional knowledge-based features, our ESA-based method builds a standalone classifier. Furthermore, we investigate if the results of this method could be useful as a complementary feature of our kNN-based approach.ResultsExperimental evaluations performed on large standard annotated datasets, provided by the BioASQ organizers, show that the kNN-based method with the Random Forest learning algorithm achieves good performances compared with the current state-of-the-art methods, reaching a competitive f-measure of 0.55% while the ESA-based approach surprisingly yielded reserved results.ConclusionsWe have proposed simple classification methods suitable to annotate textual documents using only partial information. They are therefore adequate for large multi-label classification and particularly in the biomedical domain. Thus, our work contributes to the extraction of relevant information from unstructured documents in order to facilitate their automated processing. Consequently, it could be used for various purposes, including document indexing, information retrieval, etc.

##### Abstract (translated by Google)
随着文本数据量的不断增长，识别文本文档的重要主题的自动化方法越来越受到关注。在这方面做了很多努力，但仍然是一个真正的挑战。此外，这个问题更为复杂，因为全文并不总是免费提供。然后，只使用部分信息来注释这些文件是有希望的，但仍然是一个非常雄心勃勃的问题。方法我们提出了两种分类方法：基于k-近邻（kNN）的方法和基于显式语义分析（ESA）的方法。尽管基于kNN的方法在文本分类中被广泛使用，但是在处理部分信息的特定分类问题中还需要改进。与现有的基于kNN的方法相比，我们的方法使用经典的机器学习（ML）算法对标签进行排序。为了改善分类器的性能，还研究了其他特征。另外，执行几种学习算法与用于确定相关主题的数目的各种技术的组合。另一方面，ESA对于这个分类任务似乎很有前途，因为它在相关问题上产生了有趣的结果，如文本之间的语义相关性计算和文本分类。与现有的使用ESA来丰富带有额外知识的特征的方法相比，我们基于ESA的方法构建了一个独立的分类器。此外，我们调查这种方法的结果是否可以作为我们的基于kNN的方法的补充特征是有用的。结果对由BioASQ组织者提供的大标准注释数据集进行的实验评估显示基于kNN的方法与随机森林学习算法与当前最先进的方法相比具有良好的性能，达到了0.55％的竞争性f-度量，而基于ESA的方法却令人惊讶地得出了保留的结果。结论我们提出了简单的分类方法，适用于注释文本文档只有部分信息。因此，它们适用于大型多标签分类，特别是在生物医学领域。因此，我们的工作有助于从非结构化文档中提取相关信息，以促进其自动化处理。因此，它可以用于各种目的，包括文件索引，信息检索等。

##### URL
[https://arxiv.org/abs/1606.02976](https://arxiv.org/abs/1606.02976)

##### PDF
[https://arxiv.org/pdf/1606.02976](https://arxiv.org/pdf/1606.02976)

