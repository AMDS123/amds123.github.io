---
layout: post
title: "A Sequential Model for Classifying Temporal Relations between Intra-Sentence Events"
date: 2017-07-23 20:47:02
categories: arXiv_CL
tags: arXiv_CL RNN Classification Relation
author: Prafulla Kumar Choubey, Ruihong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a sequential model for temporal relation classification between intra-sentence events. The key observation is that the overall syntactic structure and compositional meanings of the multi-word context between events are important for distinguishing among fine-grained temporal relations. Specifically, our approach first extracts a sequence of context words that indicates the temporal relation between two events, which well align with the dependency path between two event mentions. The context word sequence, together with a parts-of-speech tag sequence and a dependency relation sequence that are generated corresponding to the word sequence, are then provided as input to bidirectional recurrent neural network (LSTM) models. The neural nets learn compositional syntactic and semantic representations of contexts surrounding the two events and predict the temporal relation between them. Evaluation of the proposed approach on TimeBank corpus shows that sequential modeling is capable of accurately recognizing temporal relations between events, which outperforms a neural net model using various discrete features as input that imitates previous feature based models.

##### Abstract (translated by Google)
我们提出了一个序列模型，用于句子内部事件之间的时间关系分类。关键的观察是事件之间的多词语境的整体句法结构和组合意义对于细粒度时间关系的区分是重要的。具体而言，我们的方法首先提取一系列的上下文单词，指示两个事件之间的时间关系，这与两个事件提及之间的依赖性路径很好地对齐。然后将上下文单词序列连同对应于单词序列而生成的词性标签序列和依赖性关系序列一起作为双向递归神经网络（LSTM）模型的输入。神经网络学习围绕这两个事件的组合语法和语义表示，并预测它们之间的时间关系。对TimeBank语料库提出的方法的评估表明，顺序建模能够准确地识别事件之间的时间关系，其优于使用各种离散特征作为模仿先前基于特征的模型的输入的神经网络模型。

##### URL
[https://arxiv.org/abs/1707.07343](https://arxiv.org/abs/1707.07343)

##### PDF
[https://arxiv.org/pdf/1707.07343](https://arxiv.org/pdf/1707.07343)

