---
layout: post
title: "R-Transformer: Recurrent Neural Network Enhanced Transformer"
date: 2019-07-12 04:01:57
categories: arXiv_CV
tags: arXiv_CV Attention Embedding RNN
author: Zhiwei Wang, Yao Ma, Zitao Liu, Jiliang Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks have long been the dominating choice for sequence modeling. However, it severely suffers from two issues: impotent in capturing very long-term dependencies and unable to parallelize the sequential computation procedure. Therefore, many non-recurrent sequence models that are built on convolution and attention operations have been proposed recently. Notably, models with multi-head attention such as Transformer have demonstrated extreme effectiveness in capturing long-term dependencies in a variety of sequence modeling tasks. Despite their success, however, these models lack necessary components to model local structures in sequences and heavily rely on position embeddings that have limited effects and require a considerable amount of design efforts. In this paper, we propose the R-Transformer which enjoys the advantages of both RNNs and the multi-head attention mechanism while avoids their respective drawbacks. The proposed model can effectively capture both local structures and global long-term dependencies in sequences without any use of position embeddings. We evaluate R-Transformer through extensive experiments with data from a wide range of domains and the empirical results show that R-Transformer outperforms the state-of-the-art methods by a large margin in most of the tasks. We have made the code publicly available at \url{https://github.com/DSE-MSU/R-transformer}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05572](http://arxiv.org/abs/1907.05572)

##### PDF
[http://arxiv.org/pdf/1907.05572](http://arxiv.org/pdf/1907.05572)

