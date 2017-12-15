---
layout: post
title: "Single-Queue Decoding for Neural Machine Translation"
date: 2017-07-08 06:13:11
categories: arXiv_CL
tags: arXiv_CL
author: Raphael Shu, Hideki Nakayama
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation models rely on the beam search algorithm for decoding. In practice, we found that the quality of hypotheses in the search space is negatively affected owing to the fixed beam size. To mitigate this problem, we store all hypotheses in a single priority queue and use a universal score function for hypothesis selection. The proposed algorithm is more flexible as the discarded hypotheses can be revisited in a later step. We further design a penalty function to punish the hypotheses that tend to produce a final translation that is much longer or shorter than expected. Despite its simplicity, we show that the proposed decoding algorithm is able to select hypotheses with better qualities and improve the translation performance.

##### Abstract (translated by Google)
神经机器翻译模型依靠波束搜索算法进行解码。在实践中，我们发现由于固定的光束尺寸，搜索空间中假设的质量受到了负面影响。为了缓解这个问题，我们将所有假设存储在一个优先级队列中，并使用通用分数函数进行假设选择。所提出的算法更灵活，因为丢弃的假设可以在后面的步骤中重新讨论。我们进一步设计惩罚函数来惩罚倾向于产生比期望的更长或更短的最终翻译的假设。尽管简单，我们表明，提出的解码算法能够选择质量较好的假设，并提高翻译性能。

##### URL
[https://arxiv.org/abs/1707.01830](https://arxiv.org/abs/1707.01830)

##### PDF
[https://arxiv.org/pdf/1707.01830](https://arxiv.org/pdf/1707.01830)

