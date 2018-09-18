---
layout: post
title: "Answering Science Exam Questions Using Query Rewriting with Background Knowledge"
date: 2018-09-15 14:49:23
categories: arXiv_AI
tags: arXiv_AI Knowledge QA
author: Ryan Musa, Xiaoyan Wang, Achille Fokoue, Nicholas Mattei, Maria Chang, Pavan Kapanipathi, Bassem Makni, Kartik Talamadupula, Michael Witbrock
mathjax: true
---

* content
{:toc}

##### Abstract
Open-domain question answering (QA) is an important problem in AI and NLP that is emerging as a bellwether for progress on the generalizability of AI methods and techniques. Much of the progress in open-domain QA systems has been realized through advances in information retrieval methods and corpus construction. In this paper, we focus on the recently introduced ARC Challenge dataset, which contains 2,590 multiple choice questions authored for grade-school science exams. These questions are selected to be the most challenging for current QA systems, and current state of the art performance is only slightly better than random chance. We present a system that rewrites a given question into queries that are used to retrieve supporting text from a large corpus of science-related text. Our rewriter is able to incorporate background knowledge from ConceptNet and -- in tandem with a generic textual entailment system trained on SciTail that identifies support in the retrieved results -- outperforms several strong baselines on the end-to-end QA task despite only being trained to identify essential terms in the original source question. We use a generalizable decision methodology over the retrieved evidence and answer candidates to select the best answer. By combining query rewriting, background knowledge, and textual entailment our system is able to outperform several strong baselines on the ARC dataset.

##### Abstract (translated by Google)
开放式域名问答（QA）是AI和NLP中的一个重要问题，它正在成为人工智能方法和技术普遍化进程的领头羊。通过信息检索方法和语料库构建的进步，实现了开放域QA系统的大部分进步。在本文中，我们将重点介绍最近推出的ARC Challenge数据集，其中包含2,590个针对小学科学考试的多项选择题。选择这些问题对于当前的QA系统来说是最具挑战性的，并且当前的现有技术性能仅比随机机会略好。我们提出了一个系统，该系统将给定问题重写为用于从大量科学相关文本中检索支持文本的查询。我们的重写器能够整合来自ConceptNet的背景知识，并且与在SciTail上训练的通用文本蕴涵系统相结合，可识别检索结果中的支持 - 尽管只是经过培训，但在端到端QA任务方面优于几个强大的基线确定原始来源问题中的基本术语。我们对检索到的证据使用一般化的决策方法，并回答候选人选择最佳答案。通过结合查询重写，背景知识和文本蕴涵，我们的系统能够胜过ARC数据集上的几个强基线。

##### URL
[http://arxiv.org/abs/1809.05726](http://arxiv.org/abs/1809.05726)

##### PDF
[http://arxiv.org/pdf/1809.05726](http://arxiv.org/pdf/1809.05726)

