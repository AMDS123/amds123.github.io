---
layout: post
title: "Engineering Deep Representations for Modeling Aesthetic Perception"
date: 2019-08-08 05:40:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yanxiang Chen, Yuxing Hu, Luming Zhang, Ping Li, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Many aesthetic models in computer vision suffer from two shortcomings: 1) the low descriptiveness and interpretability of those hand-crafted aesthetic criteria (i.e., nonindicative of region-level aesthetics), and 2) the difficulty of engineering aesthetic features adaptively and automatically toward different image sets. To remedy these problems, we develop a deep architecture to learn aesthetically-relevant visual attributes from Flickr1, which are localized by multiple textual attributes in a weakly-supervised setting. More specifically, using a bag-ofwords (BoW) representation of the frequent Flickr image tags, a sparsity-constrained subspace algorithm discovers a compact set of textual attributes (e.g., landscape and sunset) for each image. Then, a weakly-supervised learning algorithm projects the textual attributes at image-level to the highly-responsive image patches at pixel-level. These patches indicate where humans look at appealing regions with respect to each textual attribute, which are employed to learn the visual attributes. Psychological and anatomical studies have shown that humans perceive visual concepts hierarchically. Hence, we normalize these patches and feed them into a five-layer convolutional neural network (CNN) to mimick the hierarchy of human perceiving the visual attributes. We apply the learned deep features on image retargeting, aesthetics ranking, and retrieval. Both subjective and objective experimental results thoroughly demonstrate the competitiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1605.07699](http://arxiv.org/abs/1605.07699)

##### PDF
[http://arxiv.org/pdf/1605.07699](http://arxiv.org/pdf/1605.07699)

