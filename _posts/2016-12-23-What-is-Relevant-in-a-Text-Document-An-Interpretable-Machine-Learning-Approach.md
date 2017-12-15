---
layout: post
title: "'What is Relevant in a Text Document?': An Interpretable Machine Learning Approach"
date: 2016-12-23 00:31:30
categories: arXiv_CL
tags: arXiv_CL Sentiment CNN Classification Prediction
author: Leila Arras, Franziska Horn, Grégoire Montavon, Klaus-Robert Müller, Wojciech Samek
mathjax: true
---

* content
{:toc}

##### Abstract
Text documents can be described by a number of abstract concepts such as semantic category, writing style, or sentiment. Machine learning (ML) models have been trained to automatically map documents to these abstract concepts, allowing to annotate very large text collections, more than could be processed by a human in a lifetime. Besides predicting the text's category very accurately, it is also highly desirable to understand how and why the categorization process takes place. In this paper, we demonstrate that such understanding can be achieved by tracing the classification decision back to individual words using layer-wise relevance propagation (LRP), a recently developed technique for explaining predictions of complex non-linear classifiers. We train two word-based ML models, a convolutional neural network (CNN) and a bag-of-words SVM classifier, on a topic categorization task and adapt the LRP method to decompose the predictions of these models onto words. Resulting scores indicate how much individual words contribute to the overall classification decision. This enables one to distill relevant information from text documents without an explicit semantic information extraction step. We further use the word-wise relevance scores for generating novel vector-based document representations which capture semantic information. Based on these document vectors, we introduce a measure of model explanatory power and show that, although the SVM and CNN models perform similarly in terms of classification accuracy, the latter exhibits a higher level of explainability which makes it more comprehensible for humans and potentially more useful for other applications.

##### Abstract (translated by Google)
文本文档可以用一些抽象的概念来描述，如语义范畴，写作风格或情感。机器学习（ML）模型已被训练成自动将文档映射到这些抽象概念，从而允许注释非常大的文本集合，而不是一生中可以由人类处理的文本集合。除了非常准确地预测文本的类别之外，理解分类过程如何发生和为什么发生也是非常理想的。在本文中，我们证明，通过使用分层相关传播（LRP）（一种最近开发的用于解释复杂非线性分类器的预测的技术）将分类决策追溯到单个词来实现这种理解。我们在主题分类任务上训练两个基于词的ML模型，一个卷积神经网络（CNN）和一个词袋SVM分类器，并且调整LRP方法以将这些模型的预测分解成单词。得出的分数表明有多少单词对总体分类决定有贡献。这使得能够在没有明确的语义信息提取步骤的情况下从文本文档中提取相关信息。我们进一步使用单词相关性分数来生成捕获语义信息的基于矢量的新颖文档表示。基于这些文档向量，我们引入了模型解释能力的量度，并且表明，虽然支持向量机模型和CNN模型在分类准确性方面表现相似，但后者表现出更高的可解释性水平，这使得人们更容易理解，对其他应用程序有用。

##### URL
[https://arxiv.org/abs/1612.07843](https://arxiv.org/abs/1612.07843)

##### PDF
[https://arxiv.org/pdf/1612.07843](https://arxiv.org/pdf/1612.07843)

