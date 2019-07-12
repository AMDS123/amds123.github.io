---
layout: post
title: "Weakly Supervised Person Re-ID: Differentiable Graphical Learning and A New Benchmark"
date: 2019-07-11 16:01:41
categories: arXiv_AI
tags: arXiv_AI Re-identification Weakly_Supervised Person_Re-identification
author: Guangrun Wang, Guangcong Wang, Xujie Zhang, Jianhuang Lai, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) benefits greatly from the accurate annotations of existing datasets (e.g., CUHK03 \cite{li2014deepreid} and Market-1501 \cite{zheng2015scalable}), which are quite expensive because each image in these datasets has to be assigned with a proper label. In this work, we ease the annotation of Re-ID by replacing the accurate annotation with inaccurate annotation, i.e., we group the images into bags in terms of time and assign a bag-level label for each bag. This greatly reduces the annotation effort and leads to the creation of a large-scale Re-ID benchmark called SYSU-30$k$. The new benchmark contains $30k$ categories of persons, which is about $20$ times larger than CUHK03 ($1.3k$ categories) and Market-1501 ($1.5k$ categories), and $30$ times larger the ImageNet ($1k$ categories). It sums up to 29,606,918 images. Learning a Re-ID model with bag-level annotation is called the weakly supervised Re-ID problem. To solve this problem, we introduce a differentiable graphical model to capture the dependencies from all images in a bag and generate a reliable pseudo label for each person image. The pseudo label is further used to supervise the learning of the Re-ID model. When compared with the fully supervised Re-ID models, our method achieves the state-of-the-art performance on SYSU-30$k$ and other datasets. The code, dataset, and pretrained model will be available at \url{https://github.com/wanggrun/SYSU-30k}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03845](http://arxiv.org/abs/1904.03845)

##### PDF
[http://arxiv.org/pdf/1904.03845](http://arxiv.org/pdf/1904.03845)

