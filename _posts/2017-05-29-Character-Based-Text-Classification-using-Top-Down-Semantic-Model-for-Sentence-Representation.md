---
layout: post
title: "Character-Based Text Classification using Top Down Semantic Model for Sentence Representation"
date: 2017-05-29 15:53:00
categories: arXiv_CL
tags: arXiv_CL Attention Text_Classification CNN RNN Classification Deep_Learning
author: Zhenzhou Wu, Xin Zheng, Daniel Dahlmeier
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of deep learning on many fronts especially image and speech, its application in text classification often is still not as good as a simple linear SVM on n-gram TF-IDF representation especially for smaller datasets. Deep learning tends to emphasize on sentence level semantics when learning a representation with models like recurrent neural network or recursive neural network, however from the success of TF-IDF representation, it seems a bag-of-words type of representation has its strength. Taking advantage of both representions, we present a model known as TDSM (Top Down Semantic Model) for extracting a sentence representation that considers both the word-level semantics by linearly combining the words with attention weights and the sentence-level semantics with BiLSTM and use it on text classification. We apply the model on characters and our results show that our model is better than all the other character-based and word-based convolutional neural network models by \cite{zhang15} across seven different datasets with only 1\% of their parameters. We also demonstrate that this model beats traditional linear models on TF-IDF vectors on small and polished datasets like news article in which typically deep learning models surrender.

##### Abstract (translated by Google)
尽管在许多方面尤其是图像和语音方面的深度学习取得了成功，但其在文本分类中的应用仍然不如在n-gram TF-IDF表示上的简单线性SVM，特别是对于较小的数据集。深度学习在用递归神经网络或递归神经网络等模型学习表示时倾向于强调句子级别的语义，然而从TF-IDF表示的成功看来，似乎是一种袋子式的表示方式。利用这两种表示方法，我们提出了一种称为TDSM（自上而下的语义模型）的模型，用于通过用BiLSTM将具有注意力权重的单词与句子级语义进行线性组合来考虑词语级别语义，并使用它在文本分类上。我们将这个模型应用到字符上，我们的结果表明，我们的模型比其他所有基于字符和基于单词的卷积神经网络模型在7个不同的数据集上都好，只有1％的参数。我们还证明，这种模型击败传统的线性模型TF  -  IDF载体上的小型和抛光的数据集，如通常深度学习模型投降的新闻文章。

##### URL
[https://arxiv.org/abs/1705.10586](https://arxiv.org/abs/1705.10586)

##### PDF
[https://arxiv.org/pdf/1705.10586](https://arxiv.org/pdf/1705.10586)

