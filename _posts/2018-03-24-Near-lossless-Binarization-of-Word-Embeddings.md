---
layout: post
title: "Near-lossless Binarization of Word Embeddings"
date: 2018-03-24 06:21:56
categories: arXiv_CL
tags: arXiv_CL Regularization Embedding Inference Relation
author: Julien Tissier, Amaury Habrard, Christophe Gravier
mathjax: true
---

* content
{:toc}

##### Abstract
Is it possible to learn binary word embeddings of arbitrary size from their real-value counterparts with (almost) no loss in task performance? If so, inferences performed in downstream NLP applications would benefit a massive speed-up brought by binary representations. In this paper, we derive an autoencoder architecture to learn semantic preserving binary embeddings from existing real-value ones. A binary encoder requires an element-wise function that outputs a bit given a real value - it is unfortunately highly non-differentiable. We propose to use the same parameters matrix for the encoder and the decoder so that we are able to learn weights using the decoder. We also show that it is possible and desirable to minimize the correlation between the different binary features at training time through ad hoc regularization. The learned binary codes can be of arbitrary sizes, and the binary representations yield (almost) the same performances than their real-value counterparts. Finally, we show that we are able to recon- struct semantic-preserving real-value embeddings from the binary embeddings - the cherry on top.

##### Abstract (translated by Google)
是否有可能从任何大小的实值对象中学习任意大小的二进制字嵌入（几乎）没有任何性能损失？如果是这样，那么在下游NLP应用程序中执行的推论将有利于二进制表示带来的大规模加速。在本文中，我们推导了一个自动编码器体系结构，用于从现有的实数值中学习语义保留二进制嵌入。一个二进制编码器需要一个元素智能功能，输出一个给定真实值的位 - 它不幸是高度不可微分的。我们建议为编码器和解码器使用相同的参数矩阵，以便我们能够使用解码器学习权重。我们还表明，通过临时正则化在训练时间最小化不同二进制特征之间的相关性是可能的和期望的。学习的二进制代码可以是任意大小的，并且二进制表示产生（几乎）与其实值对应表现相同的性能。最后，我们展示了我们能够从二进制嵌入中重构保留语义保留的实值嵌入 - 顶层的樱桃。

##### URL
[https://arxiv.org/abs/1803.09065](https://arxiv.org/abs/1803.09065)

##### PDF
[https://arxiv.org/pdf/1803.09065](https://arxiv.org/pdf/1803.09065)

