---
layout: post
title: "Bilateral Multi-Perspective Matching for Natural Language Sentences"
date: 2017-07-14 19:45:07
categories: arXiv_SD
tags: arXiv_SD Inference RNN
author: Zhiguo Wang, Wael Hamza, Radu Florian
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language sentence matching is a fundamental technology for a variety of tasks. Previous approaches either match sentences from a single direction or only apply single granular (word-by-word or sentence-by-sentence) matching. In this work, we propose a bilateral multi-perspective matching (BiMPM) model under the "matching-aggregation" framework. Given two sentences $P$ and $Q$, our model first encodes them with a BiLSTM encoder. Next, we match the two encoded sentences in two directions $P \rightarrow Q$ and $P \leftarrow Q$. In each matching direction, each time step of one sentence is matched against all time-steps of the other sentence from multiple perspectives. Then, another BiLSTM layer is utilized to aggregate the matching results into a fix-length matching vector. Finally, based on the matching vector, the decision is made through a fully connected layer. We evaluate our model on three tasks: paraphrase identification, natural language inference and answer sentence selection. Experimental results on standard benchmark datasets show that our model achieves the state-of-the-art performance on all tasks.

##### Abstract (translated by Google)
自然语言句子匹配是各种任务的基本技术。先前的方法要么从单一方向匹配句子，要么仅应用单个粒度（逐字或逐句）匹配。在这项工作中，我们在“匹配 - 聚合”框架下提出了一个双边多视角匹配（BiMPM）模型。给定两个句子$ P $和$ Q $，我们的模型首先用BiLSTM编码器对它们进行编码。接下来，我们在两个方向$ P \ rightarrow Q $和$ P \ leftarrow Q $上匹配两个编码句子。在每个匹配方向上，一个句子的每个时间步从多个角度与另一个句子的所有时间步匹配。然后，利用另一个BiLSTM层将匹配结果聚合成固定长度匹配矢量。最后，根据匹配向量，通过完全连通的层进行决策。我们评估我们的模型的三个任务：释义识别，自然语言推理和回答句子选择。标准基准数据集上的实验结果表明，我们的模型在所有任务上达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1702.03814](https://arxiv.org/abs/1702.03814)

##### PDF
[https://arxiv.org/pdf/1702.03814](https://arxiv.org/pdf/1702.03814)

