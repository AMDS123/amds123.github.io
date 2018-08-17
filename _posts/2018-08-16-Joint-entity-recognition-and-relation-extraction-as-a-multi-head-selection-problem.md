---
layout: post
title: "Joint entity recognition and relation extraction as a multi-head selection problem"
date: 2018-08-16 14:51:57
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Relation Recognition
author: Giannis Bekoulis, Johannes Deleu, Thomas Demeester, Chris Develder
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art models for joint entity recognition and relation extraction strongly rely on external natural language processing (NLP) tools such as POS (part-of-speech) taggers and dependency parsers. Thus, the performance of such joint models depends on the quality of the features obtained from these NLP tools. However, these features are not always accurate for various languages and contexts. In this paper, we propose a joint neural model which performs entity recognition and relation extraction simultaneously, without the need of any manually extracted features or the use of any external tool. Specifically, we model the entity recognition task using a CRF (Conditional Random Fields) layer and the relation extraction task as a multi-head selection problem (i.e., potentially identify multiple relations for each entity). We present an extensive experimental setup, to demonstrate the effectiveness of our method using datasets from various contexts (i.e., news, biomedical, real estate) and languages (i.e., English, Dutch). Our model outperforms the previous neural models that use automatically extracted features, while it performs within a reasonable margin of feature-based neural models, or even beats them.

##### Abstract (translated by Google)
用于联合实体识别和关系提取的最先进模型强烈依赖于外部自然语言处理（NLP）工具，例如POS（词性）标记器和依赖性解析器。因此，这种联合模型的性能取决于从这些NLP工具获得的特征的质量。但是，对于各种语言和上下文，这些功能并不总是准确的。在本文中，我们提出了一种联合神经模型，它同时执行实体识别和关系提取，无需任何手动提取的功能或使用任何外部工具。具体地，我们使用CRF（条件随机场）层和关系提取任务将实体识别任务建模为多头选择问题（即，潜在地识别每个实体的多个关系）。我们提供了一个广泛的实验设置，以证明我们的方法使用来自各种环境（即新闻，生物医学，房地产）和语言（即英语，荷兰语）的数据集的有效性。我们的模型优于以前使用自动提取特征的神经模型，同时它在基于特征的神经模型的合理范围内执行，甚至胜过它们。

##### URL
[http://arxiv.org/abs/1804.07847](http://arxiv.org/abs/1804.07847)

##### PDF
[http://arxiv.org/pdf/1804.07847](http://arxiv.org/pdf/1804.07847)

