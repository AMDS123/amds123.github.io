---
layout: post
title: "How should we evaluate supervised hashing?"
date: 2017-08-10 17:00:50
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification
author: Alexandre Sablayrolles, Matthijs Douze, Hervé Jégou, Nicolas Usunier
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing produces compact representations for documents, to perform tasks like classification or retrieval based on these short codes. When hashing is supervised, the codes are trained using labels on the training data. This paper first shows that the evaluation protocols used in the literature for supervised hashing are not satisfactory: we show that a trivial solution that encodes the output of a classifier significantly outperforms existing supervised or semi-supervised methods, while using much shorter codes. We then propose two alternative protocols for supervised hashing: one based on retrieval on a disjoint set of classes, and another based on transfer learning to new classes. We provide two baseline methods for image-related tasks to assess the performance of (semi-)supervised hashing: without coding and with unsupervised codes. These baselines give a lower- and upper-bound on the performance of a supervised hashing scheme.

##### Abstract (translated by Google)
散列生成文档的紧凑表示，执行基于这些短代码的分类或检索等任务。当监督散列时，代码在训练数据上使用标签进行训练。本文首先表明，文献中用于监督散列的评估协议并不令人满意：我们表明，对分类器的输出进行编码的一个简单的解决方案显着优于现有的监督或半监督方法，而使用更短的代码。然后，我们提出了两个监督散列的可选协议：一个基于对不相交的类集进行检索，另一个基于对新类的传递学习。我们提供了两个图像相关任务的基线方法来评估（半）监督散列的性能：无编码和无监督代码。这些基线给出了一个监督哈希方案的性能的上限和下限。

##### URL
[https://arxiv.org/abs/1609.06753](https://arxiv.org/abs/1609.06753)

##### PDF
[https://arxiv.org/pdf/1609.06753](https://arxiv.org/pdf/1609.06753)

