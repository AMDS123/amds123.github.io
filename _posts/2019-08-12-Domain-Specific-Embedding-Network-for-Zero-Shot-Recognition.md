---
layout: post
title: "Domain-Specific Embedding Network for Zero-Shot Recognition"
date: 2019-08-12 14:32:50
categories: arXiv_CV
tags: arXiv_CV Embedding Relation Recognition
author: Shaobo Min, Hantao Yao, Hongtao Xie, Zheng-Jun Zha, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Learning (ZSL) seeks to recognize a sample from either seen or unseen domain by projecting the image data and semantic labels into a joint embedding space. However, most existing methods directly adapt a well-trained projection from one domain to another, thereby ignoring the serious bias problem caused by domain differences. To address this issue, we propose a novel Domain-Specific Embedding Network (DSEN) that can apply specific projections to different domains for unbiased embedding, as well as several domain constraints. In contrast to previous methods, the DSEN decomposes the domain-shared projection function into one domain-invariant and two domain-specific sub-functions to explore the similarities and differences between two domains. To prevent the two specific projections from breaking the semantic relationship, a semantic reconstruction constraint is proposed by applying the same decoder function to them in a cycle consistency way. Furthermore, a domain division constraint is developed to directly penalize the margin between real and pseudo image features in respective seen and unseen domains, which can enlarge the inter-domain difference of visual features. Extensive experiments on four public benchmarks demonstrate the effectiveness of DSEN with an average of $9.2\%$ improvement in terms of harmonic mean. The code is available in \url{this https URL}.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.04174](https://arxiv.org/abs/1908.04174)

##### PDF
[https://arxiv.org/pdf/1908.04174](https://arxiv.org/pdf/1908.04174)

