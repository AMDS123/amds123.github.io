---
layout: post
title: "Distributed Deep Learning for Precipitation Nowcasting"
date: 2019-08-28 22:06:42
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Siddharth Samsi, Christopher J. Mattioli, Mark S. Veillette
mathjax: true
---

* content
{:toc}

##### Abstract
Effective training of Deep Neural Networks requires massive amounts of data and compute. As a result, longer times are needed to train complex models requiring large datasets, which can severely limit research on model development and the exploitation of all available data. In this paper, this problem is investigated in the context of precipitation nowcasting, a term used to describe highly detailed short-term forecasts of precipitation and other hazardous weather. Convolutional Neural Networks (CNNs) are a powerful class of models that are well-suited for this task; however, the high resolution input weather imagery combined with model complexity required to process this data makes training CNNs to solve this task time consuming. To address this issue, a data-parallel model is implemented where a CNN is replicated across multiple compute nodes and the training batches are distributed across multiple nodes. By leveraging multiple GPUs, we show that the training time for a given nowcasting model architecture can be reduced from 59 hours to just over 1 hour. This will allow for faster iterations for improving CNN architectures and will facilitate future advancement in the area of nowcasting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10964](http://arxiv.org/abs/1908.10964)

##### PDF
[http://arxiv.org/pdf/1908.10964](http://arxiv.org/pdf/1908.10964)

