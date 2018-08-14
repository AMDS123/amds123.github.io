---
layout: post
title: "Learning to Represent Bilingual Dictionaries"
date: 2018-08-10 23:21:07
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Muhao Chen, Yingtao Tian, Haochen Chen, Kai-Wei Chang, Steven Skiena, Carlo Zaniolo
mathjax: true
---

* content
{:toc}

##### Abstract
Bilingual word embeddings have been widely used to capture the similarity of lexical semantics in different human languages. However, many applications, such as cross-lingual semantic search and question answering, can be largely benefited from the cross-lingual correspondence between sentences and lexicons. To bridge this gap, we propose a neural embedding model that leverages bilingual dictionaries. The proposed model is trained to map the literal word definitions to the cross-lingual target words, for which we explore with different sentence encoding techniques. To enhance the learning process on limited resources, our model adopts several critical learning strategies, including multi-task learning on different bridges of languages, and joint learning of the dictionary model with a bilingual word embedding model. Experimental evaluation focuses on two applications. The results of the cross-lingual reverse dictionary retrieval task show our model's promising ability of comprehending bilingual concepts based on descriptions, and highlight the effectiveness of proposed learning strategies in improving performance. Meanwhile, our model effectively addresses the bilingual paraphrase identification problem and significantly outperforms previous approaches.

##### Abstract (translated by Google)
双语词汇嵌入已被广泛用于捕捉不同人类语言中词汇语义的相似性。然而，许多应用程序，例如跨语言搜索和问答，可以在很大程度上受益于句子和词典之间的跨语言对应。为了弥合这一差距，我们提出了一种利用双语词典的神经嵌入模型。训练所提出的模型将字面词定义映射到跨语言目标词，我们使用不同的句子编码技术进行探索。为了加强有限资源的学习过程，我们的模型采用了几种批判性学习策略，包括不同语言桥梁的多任务学习，以及双语词汇嵌入模型的词典模型联合学习。实验评估侧重于两个应用。跨语言反向字典检索任务的结果表明我们的模型具有很强的理解基于描述的双语概念的能力，并突出了提出的学习策略在提高绩效方面的有效性。同时，我们的模型有效地解决了双语复述识别问题，并且明显优于以前的方法。

##### URL
[http://arxiv.org/abs/1808.03726](http://arxiv.org/abs/1808.03726)

##### PDF
[http://arxiv.org/pdf/1808.03726](http://arxiv.org/pdf/1808.03726)

