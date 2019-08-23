---
layout: post
title: "Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering"
date: 2019-08-22 02:00:53
categories: arXiv_AI
tags: arXiv_AI QA
author: Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, Bing Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
BERT model has been successfully applied to open-domain QA tasks. However, previous work trains BERT by viewing passages corresponding to the same question as independent training instances, which may cause incomparable scores for answers from different passages. To tackle this issue, we propose a multi-passage BERT model to globally normalize answer scores across all passages of the same question, and this change enables our QA model find better answers by utilizing more passages. In addition, we find that splitting articles into passages with the length of 100 words by sliding window improves performance by 4%. By leveraging a passage ranker to select high-quality passages, multi-passage BERT gains additional 2%. Experiments on four standard benchmarks showed that our multi-passage BERT outperforms all state-of-the-art models on all benchmarks. In particular, on the OpenSQuAD dataset, our model gains 21.4% EM and 21.5% $F_1$ over all non-BERT models, and 5.8% EM and 6.5% $F_1$ over BERT-based models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08167](https://arxiv.org/abs/1908.08167)

##### PDF
[https://arxiv.org/pdf/1908.08167](https://arxiv.org/pdf/1908.08167)

