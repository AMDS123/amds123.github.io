---
layout: post
title: "Embedding Semantic Relations into Word Representations"
date: 2015-05-01 11:43:34
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Detection Relation
author: Danushka Bollegala, Takanori Maehara, Ken-ichi Kawarabayashi
mathjax: true
---

* content
{:toc}

##### Abstract
Learning representations for semantic relations is important for various tasks such as analogy detection, relational search, and relation classification. Although there have been several proposals for learning representations for individual words, learning word representations that explicitly capture the semantic relations between words remains under developed. We propose an unsupervised method for learning vector representations for words such that the learnt representations are sensitive to the semantic relations that exist between two words. First, we extract lexical patterns from the co-occurrence contexts of two words in a corpus to represent the semantic relations that exist between those two words. Second, we represent a lexical pattern as the weighted sum of the representations of the words that co-occur with that lexical pattern. Third, we train a binary classifier to detect relationally similar vs. non-similar lexical pattern pairs. The proposed method is unsupervised in the sense that the lexical pattern pairs we use as train data are automatically sampled from a corpus, without requiring any manual intervention. Our proposed method statistically significantly outperforms the current state-of-the-art word representations on three benchmark datasets for proportional analogy detection, demonstrating its ability to accurately capture the semantic relations among words.

##### Abstract (translated by Google)
学习语义关系的表示对于类比检测，关系搜索和关系分类等各种任务是重要的。虽然已经有几个建议来学习单词的表征，但是明确地捕捉单词之间的语义关系的学习单词表示还没有得到发展。我们提出了一种无监督的方法来学习单词的向量表示，使学习表示对两个单词之间存在的语义关系敏感。首先，从语料库中两个词的共现语境中提取词汇模式，以表示这两个词之间存在的语义关系。其次，我们将词汇模式表示为与该词汇模式共同出现的词的表示的加权和。第三，我们训练一个二元分类器来检测关系相似与不相似的词汇模式对。所提出的方法是无监督的，因为我们用作训练数据的词汇模式对从语料库自动采样，而不需要任何人工干预。我们提出的方法在统计学上显着地胜过了目前在三个基准数据集上进行比例类比检测的当前最先进的词表示，证明了其准确地捕获词之间的语义关系的能力。

##### URL
[https://arxiv.org/abs/1505.00161](https://arxiv.org/abs/1505.00161)

##### PDF
[https://arxiv.org/pdf/1505.00161](https://arxiv.org/pdf/1505.00161)

