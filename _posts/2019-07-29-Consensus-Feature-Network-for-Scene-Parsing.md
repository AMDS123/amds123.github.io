---
layout: post
title: "Consensus Feature Network for Scene Parsing"
date: 2019-07-29 13:22:30
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Tianyi Wu, Sheng Tang, Rui Zhang, Guodong Guo, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Scene parsing is challenging as it aims to assign one of the semantic categories to each pixel in scene images. Thus, pixel-level features are desired for scene parsing. However, classification networks are dominated by the discriminative portion, so directly applying classification networks to scene parsing will result in inconsistent parsing predictions within one instance and among instances of the same category. To address this problem, we propose two transform units to learn pixel-level consensus features. One is an Instance Consensus Transform (ICT) unit to learn the instance-level consensus features by aggregating features within the same instance. The other is a Category Consensus Transform (CCT) unit to pursue category-level consensus features through keeping the consensus of features among instances of the same category in scene images. The proposed ICT and CCT units are lightweight, data-driven and end-to-end trainable. The features learned by the two units are more coherent in both instance-level and category-level. Furthermore, we present the Consensus Feature Network (CFNet) based on the proposed ICT and CCT units. Experiments on four scene parsing benchmarks, including Cityscapes, Pascal Context, CamVid, and COCO Stuff, show that the proposed CFNet learns pixel-level consensus feature and obtain consistent parsing results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12411](http://arxiv.org/abs/1907.12411)

##### PDF
[http://arxiv.org/pdf/1907.12411](http://arxiv.org/pdf/1907.12411)

