---
layout: post
title: "Learning to Generate Reviews and Discovering Sentiment"
date: 2017-04-06 09:48:20
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Language_Model
author: Alec Radford, Rafal Jozefowicz, Ilya Sutskever
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the properties of byte-level recurrent language models. When given sufficient amounts of capacity, training data, and compute time, the representations learned by these models include disentangled features corresponding to high-level concepts. Specifically, we find a single unit which performs sentiment analysis. These representations, learned in an unsupervised manner, achieve state of the art on the binary subset of the Stanford Sentiment Treebank. They are also very data efficient. When using only a handful of labeled examples, our approach matches the performance of strong baselines trained on full datasets. We also demonstrate the sentiment unit has a direct influence on the generative process of the model. Simply fixing its value to be positive or negative generates samples with the corresponding positive or negative sentiment.

##### Abstract (translated by Google)
我们研究字节级循环语言模型的属性。当给定足够的容量，训练数据和计算时间时，这些模型学到的表示包括对应于高级概念的解开的特征。具体而言，我们找到一个单元进行情绪分析。这些表达以无监督的方式学习，达到了斯坦福情绪树库的二元子集的艺术水平。他们也是非常有效的数据。当仅使用少数标记的例子时，我们的方法与在完整数据集上训练的强基线的性能相匹配。我们也证明情绪单元对模型的生成过程有直接的影响。简单地将它的值固定为正值或负值会产生具有相应积极或消极情绪的样本。

##### URL
[https://arxiv.org/abs/1704.01444](https://arxiv.org/abs/1704.01444)

##### PDF
[https://arxiv.org/pdf/1704.01444](https://arxiv.org/pdf/1704.01444)

