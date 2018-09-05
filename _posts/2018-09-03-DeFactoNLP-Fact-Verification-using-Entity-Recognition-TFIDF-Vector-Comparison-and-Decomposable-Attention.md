---
layout: post
title: "DeFactoNLP: Fact Verification using Entity Recognition, TFIDF Vector Comparison and Decomposable Attention"
date: 2018-09-03 09:07:17
categories: arXiv_AI
tags: arXiv_AI Attention Classification Recognition
author: Aniketh Janardhan Reddy, Gil Rocha, Diego Esteves
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe DeFactoNLP, the system we designed for the FEVER 2018 Shared Task. The aim of this task was to conceive a system that can not only automatically assess the veracity of a claim but also retrieve evidence supporting this assessment from Wikipedia. In our approach, the Wikipedia documents whose Term Frequency-Inverse Document Frequency (TFIDF) vectors are most similar to the vector of the claim and those documents whose names are similar to those of the named entities (NEs) mentioned in the claim are identified as the documents which might contain evidence. The sentences in these documents are then supplied to a textual entailment recognition module. This module calculates the probability of each sentence supporting the claim, contradicting the claim or not providing any relevant information to assess the veracity of the claim. Various features computed using these probabilities are finally used by a Random Forest classifier to determine the overall truthfulness of the claim. The sentences which support this classification are returned as evidence. Our approach achieved a 0.4277 evidence F1-score, a 0.5136 label accuracy and a 0.3833 FEVER score.

##### Abstract (translated by Google)
在本文中，我们描述了DeFactoNLP，我们为FEVER 2018共享任务设计的系统。这项任务的目的是构思一个系统，该系统不仅可以自动评估索赔的准确性，还可以从维基百科中检索支持该评估的证据。在我们的方法中，维基百科文档的术语频率 - 逆文档频率（TFIDF）向量与权利要求的向量最相似，并且那些名称与权利要求中提到的命名实体（NE）的名称相似的文档被标识为可能包含证据的文件。然后将这些文件中的句子提供给文本蕴涵识别模块。该模块计算支持索赔的每个句子的概率，与索赔相矛盾或不提供任何相关信息来评估索赔的准确性。使用这些概率计算的各种特征最终被随机森林分类器用于确定索赔的总体真实性。支持此分类的句子作为证据返回。我们的方法获得了0.4277证据F1得分，0.5136标签准确率和0.3833 FEVER得分。

##### URL
[http://arxiv.org/abs/1809.00509](http://arxiv.org/abs/1809.00509)

##### PDF
[http://arxiv.org/pdf/1809.00509](http://arxiv.org/pdf/1809.00509)

