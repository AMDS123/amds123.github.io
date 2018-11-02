---
layout: post
title: "Class-Agnostic Counting"
date: 2018-11-01 16:11:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking
author: Erika Lu, Weidi Xie, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
Nearly all existing counting methods are designed for a specific object class. Our work, however, aims to create a counting model able to count any class of object. To achieve this goal, we formulate counting as a matching problem, enabling us to exploit the image self-similarity property that naturally exists in object counting problems. We make the following three contributions: first, a Generic Matching Network (GMN) architecture that can potentially count any object in a class-agnostic manner; second, by reformulating the counting problem as one of matching objects, we can take advantage of the abundance of video data labeled for tracking, which contains natural repetitions suitable for training a counting model. Such data enables us to train the GMN. Third, to customize the GMN to different user requirements, an adapter module is used to specialize the model with minimal effort, i.e. using a few labeled examples, and adapting only a small fraction of the trained parameters. This is a form of few-shot learning, which is practical for domains where labels are limited due to requiring expert knowledge (e.g. microbiology). We demonstrate the flexibility of our method on a diverse set of existing counting benchmarks: specifically cells, cars, and human crowds. The model achieves competitive performance on cell and crowd counting datasets, and surpasses the state-of-the-art on the car dataset using only three training images. When training on the entire dataset, the proposed method outperforms all previous methods by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00472](http://arxiv.org/abs/1811.00472)

##### PDF
[http://arxiv.org/pdf/1811.00472](http://arxiv.org/pdf/1811.00472)

