---
layout: post
title: "Using Text Embeddings for Causal Inference"
date: 2019-05-29 21:29:37
categories: arXiv_CL
tags: arXiv_CL Embedding Inference Language_Model
author: Victor Veitch, Dhanya Sridhar, David M. Blei
mathjax: true
---

* content
{:toc}

##### Abstract
We address causal inference with text documents. For example, does adding a theorem to a paper affect its chance of acceptance? Does reporting the gender of a forum post author affect the popularity of the post? We estimate these effects from observational data, where they may be confounded by features of the text such as the subject or writing quality. Although the text suffices for causal adjustment, it is prohibitively high-dimensional. The challenge is to find a low-dimensional text representation that can be used in causal inference. A key insight is that causal adjustment requires only the aspects of text that are predictive of both the treatment and outcome. Our proposed method adapts deep language models to learn low-dimensional embeddings from text that predict these values well; these embeddings suffice for causal adjustment. We establish theoretical properties of this method. We study it empirically on semi-simulated and real data on paper acceptance and forum post popularity. Code is available at https://github.com/blei-lab/causal-text-embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12741](http://arxiv.org/abs/1905.12741)

##### PDF
[http://arxiv.org/pdf/1905.12741](http://arxiv.org/pdf/1905.12741)

