---
layout: post
title: "Fast Interactive Object Annotation with Curve-GCN"
date: 2019-03-16 03:14:41
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Huan Ling, Jun Gao, Amlan Kar, Wenzheng Chen, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Manually labeling objects by tracing their boundaries is a laborious process. In Polygon-RNN++ the authors proposed Polygon-RNN that produces polygonal annotations in a recurrent manner using a CNN-RNN architecture, allowing interactive correction via humans-in-the-loop. We propose a new framework that alleviates the sequential nature of Polygon-RNN, by predicting all vertices simultaneously using a Graph Convolutional Network (GCN). Our model is trained end-to-end. It supports object annotation by either polygons or splines, facilitating labeling efficiency for both line-based and curved objects. We show that Curve-GCN outperforms all existing approaches in automatic mode, including the powerful PSP-DeepLab and is significantly more efficient in interactive mode than Polygon-RNN++. Our model runs at 29.3ms in automatic, and 2.6ms in interactive mode, making it 10x and 100x faster than Polygon-RNN++.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06874](http://arxiv.org/abs/1903.06874)

##### PDF
[http://arxiv.org/pdf/1903.06874](http://arxiv.org/pdf/1903.06874)

