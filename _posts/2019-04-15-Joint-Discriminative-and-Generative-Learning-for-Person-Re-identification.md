---
layout: post
title: "Joint Discriminative and Generative Learning for Person Re-identification"
date: 2019-04-15 17:59:43
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding
author: Zhedong Zheng, Xiaodong Yang, Zhiding Yu, Liang Zheng, Yi Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) remains challenging due to significant intra-class variations across different cameras. Recently, there has been a growing interest in using generative models to augment training data and enhance the invariance to input changes. The generative pipelines in existing methods, however, stay relatively separate from the discriminative re-id learning stages. Accordingly, re-id models are often trained in a straightforward manner on the generated data. In this paper, we seek to improve learned re-id embeddings by better leveraging the generated data. To this end, we propose a joint learning framework that couples re-id learning and data generation end-to-end. Our model involves a generative module that separately encodes each person into an appearance code and a structure code, and a discriminative module that shares the appearance encoder with the generative module. By switching the appearance or structure codes, the generative module is able to generate high-quality cross-id composed images, which are online fed back to the appearance encoder and used to improve the discriminative module. The proposed joint learning framework renders significant improvement over the baseline without using generated data, leading to the state-of-the-art performance on several benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07223](http://arxiv.org/abs/1904.07223)

##### PDF
[http://arxiv.org/pdf/1904.07223](http://arxiv.org/pdf/1904.07223)

