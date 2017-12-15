---
layout: post
title: "A Neural Language Model for Dynamically Representing the Meanings of Unknown Words and Entities in a Discourse"
date: 2017-10-17 12:35:33
categories: arXiv_CL
tags: arXiv_CL Tracking Embedding RNN Language_Model
author: Sosuke Kobayashi, Naoaki Okazaki, Kentaro Inui
mathjax: true
---

* content
{:toc}

##### Abstract
This study addresses the problem of identifying the meaning of unknown words or entities in a discourse with respect to the word embedding approaches used in neural language models. We proposed a method for on-the-fly construction and exploitation of word embeddings in both the input and output layers of a neural model by tracking contexts. This extends the dynamic entity representation used in Kobayashi et al. (2016) and incorporates a copy mechanism proposed independently by Gu et al. (2016) and Gulcehre et al. (2016). In addition, we construct a new task and dataset called Anonymized Language Modeling for evaluating the ability to capture word meanings while reading. Experiments conducted using our novel dataset show that the proposed variant of RNN language model outperformed the baseline model. Furthermore, the experiments also demonstrate that dynamic updates of an output layer help a model predict reappearing entities, whereas those of an input layer are effective to predict words following reappearing entities.

##### Abstract (translated by Google)
本研究针对在神经语言模型中使用的词语嵌入方法来识别话语中的未知单词或实体的含义的问题。我们提出了一种通过跟踪上下文在神经模型的输入层和输出层中实时建造和利用字嵌入的方法。这扩展了Kobayashi等人使用的动态实体表示。 （2016），并引入Gu等人独立提出的复制机制。 （2016年）和Gulcehre等人。 （2016）。此外，我们构建了一个新的任务和数据集，称为匿名化语言建模，以评估在阅读时捕捉词义的能力。使用我们的新数据集进行的实验表明，所提出的RNN语言模型变体优于基线模型。此外，实验还表明，输出层的动态更新有助于模型预测再现的实体，而输入层的那些更有效地预测再现的实体之后的单词。

##### URL
[https://arxiv.org/abs/1709.01679](https://arxiv.org/abs/1709.01679)

##### PDF
[https://arxiv.org/pdf/1709.01679](https://arxiv.org/pdf/1709.01679)

