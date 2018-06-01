---
layout: post
title: "Multi-Mention Learning for Reading Comprehension with Neural Cascades"
date: 2018-05-30 23:27:02
categories: arXiv_CL
tags: arXiv_CL QA Attention
author: Swabha Swayamdipta, Ankur P. Parikh, Tom Kwiatkowski
mathjax: true
---

* content
{:toc}

##### Abstract
Reading comprehension is a challenging task, especially when executed across longer or across multiple evidence documents, where the answer is likely to reoccur. Existing neural architectures typically do not scale to the entire evidence, and hence, resort to selecting a single passage in the document (either via truncation or other means), and carefully searching for the answer within that passage. However, in some cases, this strategy can be suboptimal, since by focusing on a specific passage, it becomes difficult to leverage multiple mentions of the same answer throughout the document. In this work, we take a different approach by constructing lightweight models that are combined in a cascade to find the answer. Each submodel consists only of feed-forward networks equipped with an attention mechanism, making it trivially parallelizable. We show that our approach can scale to approximately an order of magnitude larger evidence documents and can aggregate information at the representation level from multiple mentions of each answer candidate across the document. Empirically, our approach achieves state-of-the-art performance on both the Wikipedia and web domains of the TriviaQA dataset, outperforming more complex, recurrent architectures.

##### Abstract (translated by Google)
阅读理解是一项具有挑战性的任务，尤其是在长时间或跨多个证据文件执行时，答案可能会再次出现。现有的神经架构通常不会扩展到整个证据，因此，可以选择文档中的单个段落（通过截断或其他方式），并仔细搜索该段落中的答案。但是，在某些情况下，这种策略可能不是最理想的，因为通过关注特定的段落，很难在整个文档中利用多个相同答案的提及。在这项工作中，我们采取了一种不同的方法，通过构建级联中的轻量级模型来找到答案。每个子模型仅由配备了关注机制的前馈网络组成，使其可以平行化。我们表明，我们的方法可以扩展到大约一个数量级的证据文件，并且可以在整个文件中的每个候选答案的多个提及的表示级汇集信息。从经验上讲，我们的方法在TriviaQA数据集的维基百科和网络域上实现了最先进的性能，超越了更复杂的循环体系结构。

##### URL
[http://arxiv.org/abs/1711.00894](http://arxiv.org/abs/1711.00894)

##### PDF
[http://arxiv.org/pdf/1711.00894](http://arxiv.org/pdf/1711.00894)

