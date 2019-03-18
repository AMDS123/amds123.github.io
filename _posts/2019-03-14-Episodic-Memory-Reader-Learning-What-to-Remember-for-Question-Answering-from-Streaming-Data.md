---
layout: post
title: "Episodic Memory Reader: Learning What to Remember for Question Answering from Streaming Data"
date: 2019-03-14 14:00:56
categories: arXiv_CL
tags: arXiv_CL QA VQA
author: Moonsu Han, Minki Kang, Hyunwoo Jung, Sung Ju Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a novel question answering (QA) task where the machine needs to read from large streaming data (long documents or videos) without knowing when the questions will be given, in which case the existing QA methods fail due to lack of scalability. To tackle this problem, we propose a novel end-to-end reading comprehension method, which we refer to as Episodic Memory Reader (EMR) that sequentially reads the input contexts into an external memory, while replacing memories that are less important for answering unseen questions. Specifically, we train an RL agent to replace a memory entry when the memory is full in order to maximize its QA accuracy at a future timepoint, while encoding the external memory using the transformer architecture to learn representations that considers relative importance between the memory entries. We validate our model on a real-world large-scale textual QA task (TriviaQA) and a video QA task (TVQA), on which it achieves significant improvements over rule-based memory scheduling policies or an RL-based baseline that learns the query-specific importance of each memory independently.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06164](http://arxiv.org/abs/1903.06164)

##### PDF
[http://arxiv.org/pdf/1903.06164](http://arxiv.org/pdf/1903.06164)

