---
layout: post
title: "Generating Multi-Sentence Abstractive Summaries of Interleaved Texts"
date: 2019-06-05 12:28:00
categories: arXiv_CL
tags: arXiv_CL Review Attention Summarization
author: Sanjeev Kumar Karn, Francine Chen, Yan-Ying Chen, Ulli Waltinger, Hinrich Sch&#xfc;tze
mathjax: true
---

* content
{:toc}

##### Abstract
In multi-participant postings, as in online chat conversations, several conversations or topic threads may take place concurrently. This leads to difficulties for readers reviewing the postings in not only following discussions but also in quickly identifying their essence. A two-step process, disentanglement of interleaved posts followed by summarization of each thread, addresses the issue, but disentanglement errors are propagated to the summarization step, degrading the overall performance. To address this, we propose an end-to-end trainable encoder-decoder network for summarizing interleaved posts. The interleaved posts are encoded hierarchically, i.e., word-to-word (words in a post) followed by post-to-post (posts in a channel). The decoder also generates summaries hierarchically, thread-to-thread (generate thread representations) followed by word-to-word (i.e., generate summary words). Additionally, we propose a hierarchical attention mechanism for interleaved text. Overall, our end-to-end trainable hierarchical framework enhances performance over a sequence to sequence framework by 8% on a synthetic interleaved texts dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01973](http://arxiv.org/abs/1906.01973)

##### PDF
[http://arxiv.org/pdf/1906.01973](http://arxiv.org/pdf/1906.01973)

