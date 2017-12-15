---
layout: post
title: "Simple Question Answering by Attentive Convolutional Neural Network"
date: 2016-10-11 14:32:13
categories: arXiv_CL
tags: arXiv_CL QA CNN Relation
author: Wenpeng Yin, Mo Yu, Bing Xiang, Bowen Zhou, Hinrich Schütze
mathjax: true
---

* content
{:toc}

##### Abstract
This work focuses on answering single-relation factoid questions over Freebase. Each question can acquire the answer from a single fact of form (subject, predicate, object) in Freebase. This task, simple question answering (SimpleQA), can be addressed via a two-step pipeline: entity linking and fact selection. In fact selection, we match the subject entity in a fact candidate with the entity mention in the question by a character-level convolutional neural network (char-CNN), and match the predicate in that fact with the question by a word-level CNN (word-CNN). This work makes two main contributions. (i) A simple and effective entity linker over Freebase is proposed. Our entity linker outperforms the state-of-the-art entity linker over SimpleQA task. (ii) A novel attentive maxpooling is stacked over word-CNN, so that the predicate representation can be matched with the predicate-focused question representation more effectively. Experiments show that our system sets new state-of-the-art in this task.

##### Abstract (translated by Google)
这项工作专注于回答Freebase的单关系问题。每个问题都可以从Freebase中的form（subject，predicate，object）的单一事实中获得答案。这个任务，简单的问题回答（SimpleQA），可以通过两步管道来解决：实体链接和事实选择。在实际选择中，我们通过一个字符级的卷积神经网络（char-CNN）将事实候选者中的主体与实体提到的实体进行匹配，并将这个事实中的谓词与一个字级的CNN （字CNN）。这项工作有两个主要贡献。 （i）提出了一个简单而有效的Freebase实体链接器。我们的实体链接器优于SimpleQA任务中最新的实体链接器。 （ii）一个新颖的注意力最大化（maxpooling）叠加在单词CNN上，使得谓词表示可以更有效地与谓词聚焦的问题表示相匹配。实验表明，我们的系统在这个任务中设置了新的最新技术。

##### URL
[https://arxiv.org/abs/1606.03391](https://arxiv.org/abs/1606.03391)

##### PDF
[https://arxiv.org/pdf/1606.03391](https://arxiv.org/pdf/1606.03391)

