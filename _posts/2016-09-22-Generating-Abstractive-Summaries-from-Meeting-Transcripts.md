---
layout: post
title: "Generating Abstractive Summaries from Meeting Transcripts"
date: 2016-09-22 15:50:50
categories: arXiv_CL
tags: arXiv_CL Summarization Text_Generation Relation
author: Siddhartha Banerjee, Prasenjit Mitra, Kazunari Sugiyama
mathjax: true
---

* content
{:toc}

##### Abstract
Summaries of meetings are very important as they convey the essential content of discussions in a concise form. Generally, it is time consuming to read and understand the whole documents. Therefore, summaries play an important role as the readers are interested in only the important context of discussions. In this work, we address the task of meeting document summarization. Automatic summarization systems on meeting conversations developed so far have been primarily extractive, resulting in unacceptable summaries that are hard to read. The extracted utterances contain disfluencies that affect the quality of the extractive summaries. To make summaries much more readable, we propose an approach to generating abstractive summaries by fusing important content from several utterances. We first separate meeting transcripts into various topic segments, and then identify the important utterances in each segment using a supervised learning approach. The important utterances are then combined together to generate a one-sentence summary. In the text generation step, the dependency parses of the utterances in each segment are combined together to create a directed graph. The most informative and well-formed sub-graph obtained by integer linear programming (ILP) is selected to generate a one-sentence summary for each topic segment. The ILP formulation reduces disfluencies by leveraging grammatical relations that are more prominent in non-conversational style of text, and therefore generates summaries that is comparable to human-written abstractive summaries. Experimental results show that our method can generate more informative summaries than the baselines. In addition, readability assessments by human judges as well as log-likelihood estimates obtained from the dependency parser show that our generated summaries are significantly readable and well-formed.

##### Abstract (translated by Google)
会议摘要非常重要，因为它们以简洁的形式传达了讨论的基本内容。一般来说，阅读和理解整个文档是费时的。因此，摘要起着重要的作用，因为读者只关心讨论的重要内容。在这项工作中，我们解决了会议文件摘要的任务。迄今为止开发的会议自动汇总系统主要是提取式的，导致难以理解的摘要难以接受。提取的话语包含影响摘录摘要质量的不合适情况。为了使摘要更具可读性，我们提出了一种通过融合几个话语的重要内容来产生抽象摘要的方法。我们首先将会议记录分成不同的主题部分，然后用监督学习的方法确定每个部分的重要话语。然后把重要的话语结合在一起生成一个句子的总结。在文本生成步骤中，将每个段中的话语的依赖性分析组合在一起以创建有向图。通过整数线性规划（ILP）获得的信息最丰富和格式良好的子图被选择为每个主题段生成一个句子摘要。 ILP公式通过利用在非会话风格的文本中更为突出的语法关系来减少不满情绪，并因此产生与人工抽象摘要相媲美的总结。实验结果表明，我们的方法可以比基线生成更多的信息摘要。另外，人类判断的可读性评估以及从依赖分析器获得的对数似然估计表明，我们生成的摘要具有明显的可读性和良好的形式。

##### URL
[https://arxiv.org/abs/1609.07033](https://arxiv.org/abs/1609.07033)

##### PDF
[https://arxiv.org/pdf/1609.07033](https://arxiv.org/pdf/1609.07033)

