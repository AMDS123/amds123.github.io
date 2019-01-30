---
layout: post
title: "Comparison of Deep Learning Approaches for Multi-Label Chest X-Ray Classification"
date: 2019-01-29 17:10:24
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Deep_Learning Relation
author: Ivo M. Baltruschat, Hannes Nickisch, Michael Grass, Tobias Knopp, Axel Saalbach
mathjax: true
---

* content
{:toc}

##### Abstract
The increased availability of X-ray image archives (e.g. the ChestX-ray14 dataset from the NIH Clinical Center) has triggered a growing interest in deep learning techniques. To provide better insight into the different approaches, and their applications to chest X-ray classification, we investigate a powerful network architecture in detail: the ResNet-50. Building on prior work in this domain, we consider transfer learning with and without fine-tuning as well as the training of a dedicated X-ray network from scratch. To leverage the high spatial resolution of X-ray data, we also include an extended ResNet-50 architecture, and a network integrating non-image data (patient age, gender and acquisition type) in the classification process. In a concluding experiment, we also investigate multiple ResNet depths (i.e. ResNet-38 and ResNet-101). In a systematic evaluation, using 5-fold re-sampling and a multi-label loss function, we compare the performance of the different approaches for pathology classification by ROC statistics and analyze differences between the classifiers using rank correlation. Overall, we observe a considerable spread in the achieved performance and conclude that the X-ray-specific ResNet-38, integrating non-image data yields the best overall results. Furthermore, class activation maps are used to understand the classification process, and a detailed analysis of the impact of non-image features is provided.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.02315](http://arxiv.org/abs/1803.02315)

##### PDF
[http://arxiv.org/pdf/1803.02315](http://arxiv.org/pdf/1803.02315)

