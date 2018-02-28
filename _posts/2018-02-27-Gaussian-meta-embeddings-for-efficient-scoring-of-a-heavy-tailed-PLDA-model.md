---
layout: post
title: "Gaussian meta-embeddings for efficient scoring of a heavy-tailed PLDA model"
date: 2018-02-27 08:55:05
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Recognition
author: Niko Brummer, Anna Silnova, Lukas Burget, Themos Stafylakis
mathjax: true
---

* content
{:toc}

##### Abstract
Embeddings in machine learning are low-dimensional representations of complex input patterns, with the property that simple geometric operations like Euclidean distances and dot products can be used for classification and comparison tasks. The proposed meta-embeddings are special embeddings that live in more general inner product spaces. They are designed to propagate uncertainty to the final output in speaker recognition and similar applications. The familiar Gaussian PLDA model (GPLDA) can be re-formulated as an extractor for Gaussian meta-embeddings (GMEs), such that likelihood ratio scores are given by Hilbert space inner products between Gaussian likelihood functions. GMEs extracted by the GPLDA model have fixed precisions and do not propagate uncertainty. We show that a generalization to heavy-tailed PLDA gives GMEs with variable precisions, which do propagate uncertainty. Experiments on NIST SRE 2010 and 2016 show that the proposed method applied to i-vectors without length normalization is up to 20% more accurate than GPLDA applied to length-normalized ivectors.

##### Abstract (translated by Google)
机器学习中的嵌入是复杂输入模式的低维表示，具有诸如欧几里得距离和点积等简单几何操作的特性，可用于分类和比较任务。所提出的元嵌入是生活在更一般的内部产品空间中的特殊嵌入。它们旨在将不确定性传播到说话人识别和类似应用中的最终输出。熟悉的高斯PLDA模型（GPLDA）可以被重新定义为高斯元嵌入（GME）的提取器，因此似然比分数由高斯似然函数之间的希尔伯特空间内积给出。 GPLDA模型提取的GME具有固定的精度，不会传播不确定性。我们表明，对重尾PLDA的泛化给GMEs提供了可变精度，这确实传播了不确定性。在NIST SRE 2010和2016上的实验表明，应用于没有长度归一化的i向量的方法比应用于长度归一化的向导的GPLDA精确度高20％。

##### URL
[https://arxiv.org/abs/1802.09777](https://arxiv.org/abs/1802.09777)

##### PDF
[https://arxiv.org/pdf/1802.09777](https://arxiv.org/pdf/1802.09777)

