---
layout: post
title: "Deep Learning for Joint Source-Channel Coding of Text"
date: 2018-02-19 20:11:36
categories: arXiv_AI
tags: arXiv_AI Embedding Deep_Learning
author: Nariman Farsad, Milind Rao, Andrea Goldsmith
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of joint source and channel coding of structured data such as natural language over a noisy channel. The typical approach to this problem in both theory and practice involves performing source coding to first compress the text and then channel coding to add robustness for the transmission across the channel. This approach is optimal in terms of minimizing end-to-end distortion with arbitrarily large block lengths of both the source and channel codes when transmission is over discrete memoryless channels. However, the optimality of this approach is no longer ensured for documents of finite length and limitations on the length of the encoding. We will show in this scenario that we can achieve lower word error rates by developing a deep learning based encoder and decoder. While the approach of separate source and channel coding would minimize bit error rates, our approach preserves semantic information of sentences by first embedding sentences in a semantic space where sentences closer in meaning are located closer together, and then performing joint source and channel coding on these embeddings.

##### Abstract (translated by Google)
我们考虑噪声信道上结构化数据如自然语言的联合信源和信道编码问题。理论和实践中对这个问题的典型方法包括执行信源编码以首先压缩文本，然后信道编码以增加通过信道传输的稳健性。当传输通过离散无记忆信道时，这种方法在使源和信道码的任意大的块长度最小化时都是最优的。但是，对于长度有限和编码长度受限的文档，不再保证该方法的最优性。我们将在这个场景中展示通过开发基于深度学习的编码器和解码器，我们可以实现较低的字错误率。尽管单独的信源和信道编码方法可以最大限度地减少误码率，但我们的方法通过首先将句子嵌入语义空间中来保留句子的语义信息，语义空间中语义更接近的句子位置更靠近，然后对这些语句执行联合源和信道编码的嵌入。

##### URL
[http://arxiv.org/abs/1802.06832](http://arxiv.org/abs/1802.06832)

##### PDF
[http://arxiv.org/pdf/1802.06832](http://arxiv.org/pdf/1802.06832)

