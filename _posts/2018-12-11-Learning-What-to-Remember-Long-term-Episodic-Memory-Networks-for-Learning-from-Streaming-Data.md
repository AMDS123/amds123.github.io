---
layout: post
title: "Learning What to Remember: Long-term Episodic Memory Networks for Learning from Streaming Data"
date: 2018-12-11 06:04:32
categories: arXiv_CV
tags: arXiv_CV RNN Memory_Networks
author: Hyunwoo Jung, Moonsu Han, Minki Kang, Sungju Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
Current generation of memory-augmented neural networks has limited scalability as they cannot efficiently process data that are too large to fit in the external memory storage. One example of this is lifelong learning scenario where the model receives unlimited length of data stream as an input which contains vast majority of uninformative entries. We tackle this problem by proposing a memory network fit for long-term lifelong learning scenario, which we refer to as Long-term Episodic Memory Networks (LEMN), that features a RNN-based retention agent that learns to replace less important memory entries based on the retention probability generated on each entry that is learned to identify data instances of generic importance relative to other memory entries, as well as its historical importance. Such learning of retention agent allows our long-term episodic memory network to retain memory entries of generic importance for a given task. We validate our model on a path-finding task as well as synthetic and real question answering tasks, on which our model achieves significant improvements over the memory augmented networks with rule-based memory scheduling as well as an RL-based baseline that does not consider relative or historical importance of the memory.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.04227](https://arxiv.org/abs/1812.04227)

##### PDF
[https://arxiv.org/pdf/1812.04227](https://arxiv.org/pdf/1812.04227)

