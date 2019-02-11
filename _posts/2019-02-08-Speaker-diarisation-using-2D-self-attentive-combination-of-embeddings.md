---
layout: post
title: "Speaker diarisation using 2D self-attentive combination of embeddings"
date: 2019-02-08 16:54:51
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Guangzhi Sun, Chao Zhang, Phil Woodland
mathjax: true
---

* content
{:toc}

##### Abstract
Speaker diarisation systems often cluster audio segments using speaker embeddings such as i-vectors and d-vectors. Since different types of embeddings are often complementary, this paper proposes a generic framework to improve performance by combining them into a single embedding, referred to as a c-vector. This combination uses a 2-dimensional (2D) self-attentive structure, which extends the standard self-attentive layer by averaging not only across time but also across different types of embeddings. Two types of 2D self-attentive structure in this paper are the simultaneous combination and the consecutive combination, adopting a single and multiple self-attentive layers respectively. The penalty term in the original self-attentive layer which is jointly minimised with the objective function to encourage diversity of annotation vectors is also modified to obtain not only different local peaks but also the overall trends in the multiple annotation vectors. Experiments on the AMI meeting corpus show that our modified penalty term improves the d- vector relative speaker error rate (SER) by 6% and 21% for d-vector systems, and a 10% further relative SER reduction can be obtained using the c-vector from our best 2D self-attentive structure.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.03190](https://arxiv.org/abs/1902.03190)

##### PDF
[https://arxiv.org/pdf/1902.03190](https://arxiv.org/pdf/1902.03190)

