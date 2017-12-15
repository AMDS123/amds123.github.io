---
layout: post
title: "Neural Question Answering at BioASQ 5B"
date: 2017-06-26 19:14:10
categories: arXiv_CL
tags: arXiv_CL QA Embedding
author: Georg Wiese, Dirk Weissenborn, Mariana Neves
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our submission to the 2017 BioASQ challenge. We participated in Task B, Phase B which is concerned with biomedical question answering (QA). We focus on factoid and list question, using an extractive QA model, that is, we restrict our system to output substrings of the provided text snippets. At the core of our system, we use FastQA, a state-of-the-art neural QA system. We extended it with biomedical word embeddings and changed its answer layer to be able to answer list questions in addition to factoid questions. We pre-trained the model on a large-scale open-domain QA dataset, SQuAD, and then fine-tuned the parameters on the BioASQ training set. With our approach, we achieve state-of-the-art results on factoid questions and competitive results on list questions.

##### Abstract (translated by Google)
本文介绍了我们提交给2017年的BioASQ挑战。我们参加了与生物医学问答（QA）有关的任务B，B阶段。我们关注事实和列表问题，使用抽象的QA模型，也就是说，我们限制我们的系统输出提供的文本片段的子字符串。在我们的系统的核心，我们使用FastQA，一个最先进的神经QA系统。我们用生物医学词汇嵌入扩展了它，并且改变了它的答案层，以便能够回答列表问题以及事实问题。我们在大规模的开放域QA数据集SQUAD上预先训练模型，然后对BioASQ训练集上的参数进行微调。通过我们的方法，我们可以在列表问题上获得关于事实问题和竞争结果的最新结果。

##### URL
[https://arxiv.org/abs/1706.08568](https://arxiv.org/abs/1706.08568)

##### PDF
[https://arxiv.org/pdf/1706.08568](https://arxiv.org/pdf/1706.08568)

