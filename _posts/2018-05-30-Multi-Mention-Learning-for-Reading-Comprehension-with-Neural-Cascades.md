---
layout: post
title: "Multi-Mention Learning for Reading Comprehension with Neural Cascades"
date: 2018-05-30 23:27:02
categories: arXiv_CV
tags: arXiv_CV QA Attention
author: Swabha Swayamdipta, Ankur P. Parikh, Tom Kwiatkowski
mathjax: true
---

* content
{:toc}

##### Abstract
Reading comprehension is a challenging task, especially when executed across longer or across multiple evidence documents, where the answer is likely to reoccur. Existing neural architectures typically do not scale to the entire evidence, and hence, resort to selecting a single passage in the document (either via truncation or other means), and carefully searching for the answer within that passage. However, in some cases, this strategy can be suboptimal, since by focusing on a specific passage, it becomes difficult to leverage multiple mentions of the same answer throughout the document. In this work, we take a different approach by constructing lightweight models that are combined in a cascade to find the answer. Each submodel consists only of feed-forward networks equipped with an attention mechanism, making it trivially parallelizable. We show that our approach can scale to approximately an order of magnitude larger evidence documents and can aggregate information at the representation level from multiple mentions of each answer candidate across the document. Empirically, our approach achieves state-of-the-art performance on both the Wikipedia and web domains of the TriviaQA dataset, outperforming more complex, recurrent architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.00894](https://arxiv.org/abs/1711.00894)

##### PDF
[https://arxiv.org/pdf/1711.00894](https://arxiv.org/pdf/1711.00894)

