---
layout: post
title: "An end-to-end Generative Retrieval Method for Sponsored Search Engine --Decoding Efficiently into a Closed Target Domain"
date: 2019-02-02 00:19:12
categories: arXiv_CL
tags: arXiv_CL NMT Inference
author: Yijiang Lian, Zhijie Chen, Jinlong Hu, Kefeng Zhang, Chunwei Yan, Muchenxuan Tong, Wenying Han, Hanju Guan, Ying Li, Ying Cao, Yang Yu, Zhigang Li, Xiaochun Liu, Yue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a generative retrieval method for sponsored search engine, which uses neural machine translation (NMT) to generate keywords directly from query. This method is completely end-to-end, which skips query rewriting and relevance judging phases in traditional retrieval systems. Different from standard machine translation, the target space in the retrieval setting is a constrained closed set, where only committed keywords should be generated. We present a Trie-based pruning technique in beam search to address this problem. The biggest challenge in deploying this method into a real industrial environment is the latency impact of running the decoder. Self-normalized training coupled with Trie-based dynamic pruning dramatically reduces the inference time, yielding a speedup of more than 20 times. We also devise an mixed online-offline serving architecture to reduce the latency and CPU consumption. To encourage the NMT to generate new keywords uncovered by the existing system, training data is carefully selected. This model has been successfully applied in Baidu's commercial search engine as a supplementary retrieval branch, which has brought a remarkable revenue improvement of more than 10 percents.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.00592](https://arxiv.org/abs/1902.00592)

##### PDF
[https://arxiv.org/pdf/1902.00592](https://arxiv.org/pdf/1902.00592)

