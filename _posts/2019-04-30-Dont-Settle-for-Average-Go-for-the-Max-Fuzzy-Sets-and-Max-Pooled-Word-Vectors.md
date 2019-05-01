---
layout: post
title: "Don't Settle for Average, Go for the Max: Fuzzy Sets and Max-Pooled Word Vectors"
date: 2019-04-30 14:08:37
categories: arXiv_CL
tags: arXiv_CL Embedding Deep_Learning
author: Vitalii Zhelezniak, Aleksandar Savkov, April Shen, Francesco Moramarco, Jack Flann, Nils Y. Hammerla
mathjax: true
---

* content
{:toc}

##### Abstract
Recent literature suggests that averaged word vectors followed by simple post-processing outperform many deep learning methods on semantic textual similarity tasks. Furthermore, when averaged word vectors are trained supervised on large corpora of paraphrases, they achieve state-of-the-art results on standard STS benchmarks. Inspired by these insights, we push the limits of word embeddings even further. We propose a novel fuzzy bag-of-words (FBoW) representation for text that contains all the words in the vocabulary simultaneously but with different degrees of membership, which are derived from similarities between word vectors. We show that max-pooled word vectors are only a special case of fuzzy BoW and should be compared via fuzzy Jaccard index rather than cosine similarity. Finally, we propose DynaMax, a completely unsupervised and non-parametric similarity measure that dynamically extracts and max-pools good features depending on the sentence pair. This method is both efficient and easy to implement, yet outperforms current baselines on STS tasks by a large margin and is even competitive with supervised word vectors trained to directly optimise cosine similarity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13264](http://arxiv.org/abs/1904.13264)

##### PDF
[http://arxiv.org/pdf/1904.13264](http://arxiv.org/pdf/1904.13264)

