---
layout: post
title: "ReCoSa: Detecting the Relevant Contexts with Self-Attention for Multi-turn Dialogue Generation"
date: 2019-07-09 04:11:15
categories: arXiv_AI
tags: arXiv_AI Attention RNN
author: Hainan Zhang, Yanyan Lan, Liang Pang, Jiafeng Guo, Xueqi Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
In multi-turn dialogue generation, response is usually related with only a few contexts. Therefore, an ideal model should be able to detect these relevant contexts and produce a suitable response accordingly. However, the widely used hierarchical recurrent encoderdecoder models just treat all the contexts indiscriminately, which may hurt the following response generation process. Some researchers try to use the cosine similarity or the traditional attention mechanism to find the relevant contexts, but they suffer from either insufficient relevance assumption or position bias problem. In this paper, we propose a new model, named ReCoSa, to tackle this problem. Firstly, a word level LSTM encoder is conducted to obtain the initial representation of each context. Then, the self-attention mechanism is utilized to update both the context and masked response representation. Finally, the attention weights between each context and response representations are computed and used in the further decoding process. Experimental results on both Chinese customer services dataset and English Ubuntu dialogue dataset show that ReCoSa significantly outperforms baseline models, in terms of both metric-based and human evaluations. Further analysis on attention shows that the detected relevant contexts by ReCoSa are highly coherent with human's understanding, validating the correctness and interpretability of ReCoSa.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05339](http://arxiv.org/abs/1907.05339)

##### PDF
[http://arxiv.org/pdf/1907.05339](http://arxiv.org/pdf/1907.05339)

