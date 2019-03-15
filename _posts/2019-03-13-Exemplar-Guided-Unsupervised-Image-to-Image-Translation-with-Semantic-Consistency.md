---
layout: post
title: "Exemplar Guided Unsupervised Image-to-Image Translation with Semantic Consistency"
date: 2019-03-13 18:30:30
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning
author: Liqian Ma, Xu Jia, Stamatios Georgoulis, Tinne Tuytelaars, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation has recently received significant attention due to advances in deep learning. Most works focus on learning either a one-to-one mapping in an unsupervised way or a many-to-many mapping in a supervised way. However, a more practical setting is many-to-many mapping in an unsupervised way, which is harder due to the lack of supervision and the complex inner- and cross-domain variations. To alleviate these issues, we propose the Exemplar Guided &amp; Semantically Consistent Image-to-image Translation (EGSC-IT) network which conditions the translation process on an exemplar image in the target domain. We assume that an image comprises of a content component which is shared across domains, and a style component specific to each domain. Under the guidance of an exemplar from the target domain we apply Adaptive Instance Normalization to the shared content component, which allows us to transfer the style information of the target domain to the source domain. To avoid semantic inconsistencies during translation that naturally appear due to the large inner- and cross-domain variations, we introduce the concept of feature masks that provide coarse semantic guidance without requiring the use of any semantic labels. Experimental results on various datasets show that EGSC-IT does not only translate the source image to diverse instances in the target domain, but also preserves the semantic consistency during the process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11145](http://arxiv.org/abs/1805.11145)

##### PDF
[http://arxiv.org/pdf/1805.11145](http://arxiv.org/pdf/1805.11145)

