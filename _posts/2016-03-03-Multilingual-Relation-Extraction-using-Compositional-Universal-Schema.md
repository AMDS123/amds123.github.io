---
layout: post
title: "Multilingual Relation Extraction using Compositional Universal Schema"
date: 2016-03-03 20:28:36
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation_Extraction Embedding Transfer_Learning Prediction Relation
author: Patrick Verga, David Belanger, Emma Strubell, Benjamin Roth, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Universal schema builds a knowledge base (KB) of entities and relations by jointly embedding all relation types from input KBs as well as textual patterns expressing relations from raw text. In most previous applications of universal schema, each textual pattern is represented as a single embedding, preventing generalization to unseen patterns. Recent work employs a neural network to capture patterns' compositional semantics, providing generalization to all possible input text. In response, this paper introduces significant further improvements to the coverage and flexibility of universal schema relation extraction: predictions for entities unseen in training and multilingual transfer learning to domains with no annotation. We evaluate our model through extensive experiments on the English and Spanish TAC KBP benchmark, outperforming the top system from TAC 2013 slot-filling using no handwritten patterns or additional annotation. We also consider a multilingual setting in which English training data entities overlap with the seed KB, but Spanish text does not. Despite having no annotation for Spanish data, we train an accurate predictor, with additional improvements obtained by tying word embeddings across languages. Furthermore, we find that multilingual training improves English relation extraction accuracy. Our approach is thus suited to broad-coverage automated knowledge base construction in a variety of languages and domains.

##### Abstract (translated by Google)
通用模式通过联合嵌入来自输入KB的所有关系类型以及表达来自原始文本的关系的文本模式来建立实体和关系的知识库（KB）。在通用模式的大多数以前的应用中，每个文本模式被表示为单个嵌入，从而防止泛化到不可见模式。最近的工作采用神经网络来捕捉模式的组成语义，提供所有可能的输入文本的概括。作为回应，本文对通用模式关系提取的覆盖范围和灵活性进行了重大的进一步改进：对未经注册的实体进行预测，对没有注释的域进行多语言传输学习。我们通过对英语和西班牙语TAC KBP基准进行广泛的实验来评估我们的模型，比使用手写模式或附加注释的TAC 2013插槽填充的顶级系统更胜一筹。我们还考虑了英语培训数据实体与种子KB重叠的多语言环境，但西班牙语文本没有。尽管没有对西班牙数据进行注释，但是我们训练了一个准确的预测器，并通过绑定跨语言的词嵌入获得了额外的改进。此外，我们发现多语言培训提高了英语关系提取的准确性。因此，我们的方法适用于各种语言和领域的广泛覆盖的自动化知识库构建。

##### URL
[https://arxiv.org/abs/1511.06396](https://arxiv.org/abs/1511.06396)

##### PDF
[https://arxiv.org/pdf/1511.06396](https://arxiv.org/pdf/1511.06396)

