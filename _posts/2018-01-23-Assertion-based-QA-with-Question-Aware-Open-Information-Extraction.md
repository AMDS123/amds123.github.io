---
layout: post
title: "Assertion-based QA with Question-Aware Open Information Extraction"
date: 2018-01-23 07:22:34
categories: arXiv_CL
tags: arXiv_CL QA
author: Zhao Yan, Duyu Tang, Nan Duan, Shujie Liu, Wendi Wang, Daxin Jiang, Ming Zhou, Zhoujun Li
mathjax: true
---

* content
{:toc}

##### Abstract
We present assertion based question answering (ABQA), an open domain question answering task that takes a question and a passage as inputs, and outputs a semi-structured assertion consisting of a subject, a predicate and a list of arguments. An assertion conveys more evidences than a short answer span in reading comprehension, and it is more concise than a tedious passage in passage-based QA. These advantages make ABQA more suitable for human-computer interaction scenarios such as voice-controlled speakers. Further progress towards improving ABQA requires richer supervised dataset and powerful models of text understanding. To remedy this, we introduce a new dataset called WebAssertions, which includes hand-annotated QA labels for 358,427 assertions in 55,960 web passages. To address ABQA, we develop both generative and extractive approaches. The backbone of our generative approach is sequence to sequence learning. In order to capture the structure of the output assertion, we introduce a hierarchical decoder that first generates the structure of the assertion and then generates the words of each field. The extractive approach is based on learning to rank. Features at different levels of granularity are designed to measure the semantic relevance between a question and an assertion. Experimental results show that our approaches have the ability to infer question-aware assertions from a passage. We further evaluate our approaches by incorporating the ABQA results as additional features in passage-based QA. Results on two datasets show that ABQA features significantly improve the accuracy on passage-based~QA.

##### Abstract (translated by Google)
我们提出基于断言的问题回答（ABQA），一个开放的领域问题回答任务，将问题和段落作为输入，输出由主体，谓语和参数列表组成的半结构化断言。一个断言在阅读理解中传达的证据比简短的答案更多，而且比基于段落的QA中单调乏味的段落更简洁。这些优势使得ABQA更适合人机交互场景，如语音控制扬声器。进一步改善ABQA需要更多的监督数据集和强大的文本理解模型。为了解决这个问题，我们引入了一个名为WebAssertions的新数据集，其中包含55,960个网页段落中的358,427个断言的手工注释QA标签。为了解决ABQA，我们开发了生成和提取方法。我们生成方法的基础是顺序学习。为了捕捉输出断言的结构，我们引入了一个分层的解码器，首先产生断言的结构，然后生成每个字段的字。采掘方法是基于学习排名。不同粒度级别的特征旨在衡量问题与断言之间的语义相关性。实验结果表明，我们的方法有能力从段落推断问题意识的断言。我们进一步评估我们的方法，将ABQA结果作为基于段落QA的附加特征。两个数据集的结果显示，ABQA特征显着提高了基于传播的QA的准确性。

##### URL
[http://arxiv.org/abs/1801.07414](http://arxiv.org/abs/1801.07414)

##### PDF
[http://arxiv.org/pdf/1801.07414](http://arxiv.org/pdf/1801.07414)

