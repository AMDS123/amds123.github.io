---
layout: post
title: "Unsupervised Part Mining for Fine-grained Image Classification"
date: 2019-02-26 14:04:58
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Jian Zhang, Runsheng Zhang, Yaping Huang, Qi Zou
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image classification remains challenging due to the large intra-class variance and small inter-class variance. Since the subtle visual differences are only in local regions of discriminative parts among subcategories, part localization is a key issue for fine-grained image classification. Most existing approaches localize object or parts in an image with object or part annotations, which are expensive and labor-consuming. To tackle this issue, we propose a fully unsupervised part mining (UPM) approach to localize the discriminative parts without even image-level annotations, which largely improves the fine-grained classification performance. We first utilize pattern mining techniques to discover frequent patterns, i.e., co-occurrence highlighted regions, in the feature maps extracted from a pre-trained convolutional neural network (CNN) model. Inspired by the fact that these relevant meaningful patterns typically hold appearance and spatial consistency, we then cluster the mined regions to obtain the cluster centers and the discriminative parts surrounding the cluster centers are generated. Importantly, any annotations and sophisticated training procedures are not used in our proposed part localization approach. Finally, a multi-stream classification network is built for aggregating the original, object-level and part-level features simultaneously. Compared with other state-of-the-art approaches, our UPM approach achieves the competitive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09941](http://arxiv.org/abs/1902.09941)

##### PDF
[http://arxiv.org/pdf/1902.09941](http://arxiv.org/pdf/1902.09941)

