---
layout: post
title: "The Natural Language Decathlon: Multitask Learning as Question Answering"
date: 2018-06-20 16:39:26
categories: arXiv_AI
tags: arXiv_AI Sentiment QA Relation_Extraction Text_Classification Summarization Transfer_Learning Inference Classification Deep_Learning Relation Recognition
author: Bryan McCann, Nitish Shirish Keskar, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has improved performance on many natural language processing (NLP) tasks individually. However, general NLP models cannot emerge within a paradigm that focuses on the particularities of a single metric, dataset, and task. We introduce the Natural Language Decathlon (decaNLP), a challenge that spans ten tasks: question answering, machine translation, summarization, natural language inference, sentiment analysis, semantic role labeling, zero-shot relation extraction, goal-oriented dialogue, semantic parsing, and commonsense pronoun resolution. We cast all tasks as question answering over a context. Furthermore, we present a new Multitask Question Answering Network (MQAN) jointly learns all tasks in decaNLP without any task-specific modules or parameters in the multitask setting. MQAN shows improvements in transfer learning for machine translation and named entity recognition, domain adaptation for sentiment analysis and natural language inference, and zero-shot capabilities for text classification. We demonstrate that the MQAN's multi-pointer-generator decoder is key to this success and performance further improves with an anti-curriculum training strategy. Though designed for decaNLP, MQAN also achieves state of the art results on the WikiSQL semantic parsing task in the single-task setting. We also release code for procuring and processing data, training and evaluating models, and reproducing all experiments for decaNLP.

##### Abstract (translated by Google)
深度学习单独提高了许多自然语言处理（NLP）任务的性能。然而，一般的NLP模型不能出现在关注单个度量，数据集和任务的特殊性的范例中。我们引入了自然语言十项全能（decaNLP）这一跨越10个任务的挑战：问答，机器翻译，摘要，自然语言推理，情感分析，语义角色标注，零点关系抽取，目标导向对话，语义分析，和常识代名词解析。我们将所有任务都视为问题回答。此外，我们提出了一个新的多任务问题应答网络（MQAN），它可以共同学习decaNLP中的所有任务，而无需在多任务设置中使用任何特定于任务的模块或参数。 MQAN显示了机器翻译和命名实体识别的转移学习，情感分析和自然语言推理的域适应以及文本分类的零射击功能方面的改进。我们证明MQAN的多指针生成器解码器是这一成功的关键，并且通过反课程培训策略可以进一步提高性能。虽然专为decaNLP设计，但MQAN还可以在单​​任务设置中的WikiSQL语义分析任务上实现最新的结果。我们还发布了用于采购和处理数据的代码，培训和评估模型，并复制了decaNLP的所有实验。

##### URL
[http://arxiv.org/abs/1806.08730](http://arxiv.org/abs/1806.08730)

##### PDF
[http://arxiv.org/pdf/1806.08730](http://arxiv.org/pdf/1806.08730)

