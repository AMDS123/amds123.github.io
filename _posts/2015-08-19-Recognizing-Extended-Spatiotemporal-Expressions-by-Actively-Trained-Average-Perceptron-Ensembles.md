---
layout: post
title: "Recognizing Extended Spatiotemporal Expressions by Actively Trained Average Perceptron Ensembles"
date: 2015-08-19 04:17:47
categories: arXiv_CL
tags: arXiv_CL Inference
author: Wei Zhang, Yang Yu, Osho Gupta, Judith Gelernter
mathjax: true
---

* content
{:toc}

##### Abstract
Precise geocoding and time normalization for text requires that location and time phrases be identified. Many state-of-the-art geoparsers and temporal parsers suffer from low recall. Categories commonly missed by parsers are: nouns used in a non- spatiotemporal sense, adjectival and adverbial phrases, prepositional phrases, and numerical phrases. We collected and annotated data set by querying commercial web searches API with such spatiotemporal expressions as were missed by state-of-the- art parsers. Due to the high cost of sentence annotation, active learning was used to label training data, and a new strategy was designed to better select training examples to reduce labeling cost. For the learning algorithm, we applied an average perceptron trained Featurized Hidden Markov Model (FHMM). Five FHMM instances were used to create an ensemble, with the output phrase selected by voting. Our ensemble model was tested on a range of sequential labeling tasks, and has shown competitive performance. Our contributions include (1) an new dataset annotated with named entities and expanded spatiotemporal expressions; (2) a comparison of inference algorithms for ensemble models showing the superior accuracy of Belief Propagation over Viterbi Decoding; (3) a new example re-weighting method for active ensemble learning that 'memorizes' the latest examples trained; (4) a spatiotemporal parser that jointly recognizes expanded spatiotemporal expressions as well as named entities.

##### Abstract (translated by Google)
精确的地理编码和文本的时间规范化要求确定位置和时间短语。许多国家最先进的地质人员和时间解析器遭受低回忆。分析者通常忽略的分类是：非时空意义上使用的名词，形容词和副词短语，介词短语和数字短语。我们通过查询商业网络搜索API来收集和注释数据集，并使用最先进的解析器错过的时空表达式。由于句子标注的成本较高，主动学习被用来标注训练数据，并设计了一个新的策略来更好地选择训练样例来降低标签成本。对于学习算法，我们应用平均感知器训练的特征隐马尔可夫模型（FHMM）。五个FHMM实例用于创建一个集合，输出短语通过投票选择。我们的集成模型在一系列的顺序标签任务上进行了测试，并且显示出有竞争力的表现。我们的贡献包括（1）一个新的数据集注释命名实体和扩展的时空表达式; （2）集合模型的推理算法的比较，显示了信赖传播与维特比解码的高精度; （3）有效集合学习的一个新的例子重新加权方法，“记忆”训练的最新例子; （4）共同识别扩展的时空表达以及命名实体的时空分析器。

##### URL
[https://arxiv.org/abs/1508.04525](https://arxiv.org/abs/1508.04525)

##### PDF
[https://arxiv.org/pdf/1508.04525](https://arxiv.org/pdf/1508.04525)

