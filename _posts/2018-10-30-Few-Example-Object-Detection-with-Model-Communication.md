---
layout: post
title: "Few-Example Object Detection with Model Communication"
date: 2018-10-30 23:51:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xuanyi Dong, Liang Zheng, Fan Ma, Yi Yang, Deyu Meng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study object detection using a large pool of unlabeled images and only a few labeled images per category, named "few-example object detection". The key challenge consists in generating trustworthy training samples as many as possible from the pool. Using few training examples as seeds, our method iterates between model training and high-confidence sample selection. In training, easy samples are generated first and, then the poorly initialized model undergoes improvement. As the model becomes more discriminative, challenging but reliable samples are selected. After that, another round of model improvement takes place. To further improve the precision and recall of the generated training samples, we embed multiple detection models in our framework, which has proven to outperform the single model baseline and the model ensemble method. Experiments on PASCAL VOC'07, MS COCO'14, and ILSVRC'13 indicate that by using as few as three or four samples selected for each category, our method produces very competitive results when compared to the state-of-the-art weakly-supervised approaches using a large number of image-level labels.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.08249](https://arxiv.org/abs/1706.08249)

##### PDF
[https://arxiv.org/pdf/1706.08249](https://arxiv.org/pdf/1706.08249)

