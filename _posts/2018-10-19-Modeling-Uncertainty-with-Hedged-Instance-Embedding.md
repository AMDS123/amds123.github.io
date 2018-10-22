---
layout: post
title: "Modeling Uncertainty with Hedged Instance Embedding"
date: 2018-10-19 15:41:25
categories: arXiv_CV
tags: arXiv_CV Image_Caption Embedding Classification Recognition
author: Seong Joon Oh, Kevin Murphy, Jiyan Pan, Joseph Roth, Florian Schroff, Andrew Gallagher
mathjax: true
---

* content
{:toc}

##### Abstract
Instance embeddings are an efficient and versatile image representation that facilitates applications like recognition, verification, retrieval, and clustering. Many metric learning methods represent the input as a single point in the embedding space. Often the distance between points is used as a proxy for match confidence. However, this can fail to represent uncertainty arising when the input is ambiguous, e.g., due to occlusion or blurriness. This work addresses this issue and explicitly models the uncertainty by hedging the location of each input in the embedding space. We introduce the hedged instance embedding (HIB) in which embeddings are modeled as random variables and the model is trained under the variational information bottleneck principle. Empirical results on our new N-digit MNIST dataset show that our method leads to the desired behavior of hedging its bets across the embedding space upon encountering ambiguous inputs. This results in improved performance for image matching and classification tasks, more structure in the learned embedding space, and an ability to compute a per-exemplar uncertainty measure that is correlated with downstream performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00319](http://arxiv.org/abs/1810.00319)

##### PDF
[http://arxiv.org/pdf/1810.00319](http://arxiv.org/pdf/1810.00319)

