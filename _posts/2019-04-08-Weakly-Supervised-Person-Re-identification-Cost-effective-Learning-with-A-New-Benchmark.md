---
layout: post
title: "Weakly Supervised Person Re-identification: Cost-effective Learning with A New Benchmark"
date: 2019-04-08 05:27:53
categories: arXiv_AI
tags: arXiv_AI Re-identification Weakly_Supervised Person_Re-identification
author: Guangrun Wang, Guangcong Wang, Xujie Zhang, Jianhuang Lai, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (ReID) benefits greatly from the accurate annotations of existing datasets (e.g., CUHK03 \cite{li2014deepreid} and Market-1501 \cite{zheng2015scalable}), which are quite expensive because each image in these datasets has to be assigned with a proper label. In this work, we explore to ease the annotation of ReID by replacing the accurate annotation with inaccurate annotation, i.e., we group the images into bags in terms of time and assign a bag-level label for each bag. This greatly reduces the annotation effort and leads to the creation of a large-scale ReID benchmark called SYSU-30$k$. The new benchmark contains $30k$ categories of persons, which is about $20$ times larger than CUHK03 ($1.3k$ categories) and Market-1501 ($1.5k$ categories), and $30$ times larger the ImageNet ($1k$ categories). It totally sums up to 29,606,918 images. Learning a ReID model with bag-level annotation is called the weakly supervised ReID problem. To solve this problem, we introduce conditional random fields (CRFs) to capture the dependencies from all images in a bag and generate a reliable pseudo label for each person image. The pseudo label is further used to supervise the learning of the ReID model. When compared with the fully supervised ReID models, our method achieves the state-of-the-art performance on SYSU-30$k$ and other datasets. The code, dataset, and pretrained model will be available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03845](http://arxiv.org/abs/1904.03845)

##### PDF
[http://arxiv.org/pdf/1904.03845](http://arxiv.org/pdf/1904.03845)

