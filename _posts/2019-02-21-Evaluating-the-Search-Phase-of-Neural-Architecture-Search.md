---
layout: post
title: "Evaluating the Search Phase of Neural Architecture Search"
date: 2019-02-21 17:11:56
categories: arXiv_CV
tags: arXiv_CV NAS
author: Christian Sciuto, Kaicheng Yu, Martin Jaggi, Claudiu Musat, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS) aims to facilitate the design of deep networks for new tasks. Existing techniques rely on two stages: searching over the architecture space and validating the best architecture. Evaluating NAS algorithms is currently solely done by comparing their results on the downstream task. While intuitive, this fails to explicitly evaluate the effectiveness of their search strategies. In this paper, we extend the NAS evaluation procedure to include the search phase. To this end, we compare the quality of the solutions obtained by NAS search policies with that of random architecture selection. We find that: (i) On average, the random policy outperforms state-of-the-art NAS algorithms; and (ii) The results and candidate rankings of NAS algorithms do not reflect the true performance of the candidate architectures. While our former finding illustrates the fact that the NAS search space has been sufficiently constrained so that random solutions yield good results, we trace the latter back to the weight sharing strategy used by state-of-the-art NAS methods. In contrast with common belief, weight sharing negatively impacts the training of good architectures, thus reducing the effectiveness of the search process. We believe that following our evaluation framework will be key to designing NAS strategies that truly discover superior architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.08142](https://arxiv.org/abs/1902.08142)

##### PDF
[https://arxiv.org/pdf/1902.08142](https://arxiv.org/pdf/1902.08142)

