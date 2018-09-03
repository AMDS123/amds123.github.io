---
layout: post
title: "Retrieve-and-Read: Multi-task Learning of Information Retrieval and Reading Comprehension"
date: 2018-08-31 08:22:12
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Kyosuke Nishida, Itsumi Saito, Atsushi Otsuka, Hisako Asano, Junji Tomita
mathjax: true
---

* content
{:toc}

##### Abstract
This study considers the task of machine reading at scale (MRS) wherein, given a question, a system first performs the information retrieval (IR) task of finding relevant passages in a knowledge source and then carries out the reading comprehension (RC) task of extracting an answer span from the passages. Previous MRS studies, in which the IR component was trained without considering answer spans, struggled to accurately find a small number of relevant passages from a large set of passages. In this paper, we propose a simple and effective approach that incorporates the IR and RC tasks by using supervised multi-task learning in order that the IR component can be trained by considering answer spans. Experimental results on the standard benchmark, answering SQuAD questions using the full Wikipedia as the knowledge source, showed that our model achieved state-of-the-art performance. Moreover, we thoroughly evaluated the individual contributions of our model components with our new Japanese dataset and SQuAD. The results showed significant improvements in the IR task and provided a new perspective on IR for RC: it is effective to teach which part of the passage answers the question rather than to give only a relevance score to the whole passage.

##### Abstract (translated by Google)
本研究考虑了机器大规模阅读（MRS）的任务，其中，在给出问题的情况下，系统首先执行信息检索（IR）任务，在知识源中找到相关的段落，然后执行阅读理解（RC）任务。从段落中提取答案范围。以前的MRS研究，其中IR组件在没有考虑答案跨度的情况下进行训练，努力准确地从大量段落中找到少量相关段落。在本文中，我们提出了一种简单有效的方法，通过使用有监督的多任务学习来结合IR和RC任务，以便通过考虑答案跨度来训练IR组件。标准基准测试的实验结果，使用完整的维基百科作为知识源来回答SQuAD问题，表明我们的模型实现了最先进的性能。此外，我们使用新的日本数据集和SQuAD彻底评估了模型组件的个体贡献。结果显示了IR任务的显着改进，并为RC提供了新的IR观点：教导段落的哪一部分回答问题而不是仅对整个段落给出相关性得分是有效的。

##### URL
[http://arxiv.org/abs/1808.10628](http://arxiv.org/abs/1808.10628)

##### PDF
[http://arxiv.org/pdf/1808.10628](http://arxiv.org/pdf/1808.10628)

