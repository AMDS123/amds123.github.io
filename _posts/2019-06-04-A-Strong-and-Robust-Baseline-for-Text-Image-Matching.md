---
layout: post
title: "A Strong and Robust Baseline for Text-Image Matching"
date: 2019-06-04 05:42:58
categories: arXiv_CV
tags: arXiv_CV Review Embedding Inference
author: Fangyu Liu, Rongtian Ye
mathjax: true
---

* content
{:toc}

##### Abstract
We review the current schemes of text-image matching models and propose improvements for both training and inference. First, we empirically show limitations of two popular loss (sum and max-margin loss) widely used in training text-image embeddings and propose a trade-off: a kNN-margin loss which 1) utilizes information from hard negatives and 2) is robust to noise as all $K$-most hardest samples are taken into account, tolerating \emph{pseudo} negatives and outliers. Second, we advocate the use of Inverted Softmax (\textsc{Is}) and Cross-modal Local Scaling (\textsc{Csls}) during inference to mitigate the so-called hubness problem in high-dimensional embedding space, enhancing scores of all metrics by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01205](http://arxiv.org/abs/1906.01205)

##### PDF
[http://arxiv.org/pdf/1906.01205](http://arxiv.org/pdf/1906.01205)

