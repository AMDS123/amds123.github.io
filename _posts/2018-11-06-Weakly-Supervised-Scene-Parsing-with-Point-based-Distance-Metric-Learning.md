---
layout: post
title: "Weakly Supervised Scene Parsing with Point-based Distance Metric Learning"
date: 2018-11-06 09:00:10
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Relation
author: Rui Qian, Yunchao Wei, Honghui Shi, Jiachen Li, Jiaying Liu, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic scene parsing is suffering from the fact that pixel-level annotations are hard to be collected. To tackle this issue, we propose a Point-based Distance Metric Learning (PDML) in this paper. PDML does not require dense annotated masks and only leverages several labeled points that are much easier to obtain to guide the training process. Concretely, we leverage semantic relationship among the annotated points by encouraging the feature representations of the intra- and inter-category points to keep consistent, i.e. points within the same category should have more similar feature representations compared to those from different categories. We formulate such a characteristic into a simple distance metric loss, which collaborates with the point-wise cross-entropy loss to optimize the deep neural networks. Furthermore, to fully exploit the limited annotations, distance metric learning is conducted across different training images instead of simply adopting an image-dependent manner. We conduct extensive experiments on two challenging scene parsing benchmarks of PASCAL-Context and ADE 20K to validate the effectiveness of our PDML, and competitive mIoU scores are achieved.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02233](https://arxiv.org/abs/1811.02233)

##### PDF
[https://arxiv.org/pdf/1811.02233](https://arxiv.org/pdf/1811.02233)

