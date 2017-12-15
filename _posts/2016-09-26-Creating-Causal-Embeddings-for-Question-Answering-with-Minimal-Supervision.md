---
layout: post
title: "Creating Causal Embeddings for Question Answering with Minimal Supervision"
date: 2016-09-26 17:50:15
categories: arXiv_CL
tags: arXiv_CL QA Embedding
author: Rebecca Sharp, Mihai Surdeanu, Peter Jansen, Peter Clark, Michael Hammond
mathjax: true
---

* content
{:toc}

##### Abstract
A common model for question answering (QA) is that a good answer is one that is closely related to the question, where relatedness is often determined using general-purpose lexical models such as word embeddings. We argue that a better approach is to look for answers that are related to the question in a relevant way, according to the information need of the question, which may be determined through task-specific embeddings. With causality as a use case, we implement this insight in three steps. First, we generate causal embeddings cost-effectively by bootstrapping cause-effect pairs extracted from free text using a small set of seed patterns. Second, we train dedicated embeddings over this data, by using task-specific contexts, i.e., the context of a cause is its effect. Finally, we extend a state-of-the-art reranking approach for QA to incorporate these causal embeddings. We evaluate the causal embedding models both directly with a casual implication task, and indirectly, in a downstream causal QA task using data from Yahoo! Answers. We show that explicitly modeling causality improves performance in both tasks. In the QA task our best model achieves 37.3% P@1, significantly outperforming a strong baseline by 7.7% (relative).

##### Abstract (translated by Google)
问答（QA）的一个通用模型是，一个好的答案是一个与问题密切相关的问题，在这个问题中，相关性通常是使用通用词汇模型（如词嵌入）来确定的。我们认为，更好的方法是根据问题的信息需要，以相关的方式寻找与问题相关的答案，这可以通过任务特定的嵌入来确定。把因果作为一个用例，我们分三步实现这个见解。首先，我们使用少量的种子模式从自由文本中提取出因果关系对，从而以低成本的方式生成因果嵌入。其次，我们使用特定于任务的上下文对这些数据进行专门的嵌入，即原因的上下文就是它的效果。最后，我们扩展了质量保证最先进的重新排名方法，以结合这些因果嵌入。我们评估因果嵌入模型直接与一个偶然的暗示任务，间接地，在下游因果QA任务使用来自雅虎的数据！解答。我们表明明确建模因果关系提高了这两个任务的性能。在质量保证任务中，我们最好的模型达到了37.3％的P1，明显比强劲的基准要好7.7％（相对）。

##### URL
[https://arxiv.org/abs/1609.08097](https://arxiv.org/abs/1609.08097)

##### PDF
[https://arxiv.org/pdf/1609.08097](https://arxiv.org/pdf/1609.08097)

