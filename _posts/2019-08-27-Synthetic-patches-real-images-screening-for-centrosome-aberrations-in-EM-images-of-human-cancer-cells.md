---
layout: post
title: "Synthetic patches, real images: screening for centrosome aberrations in EM images of human cancer cells"
date: 2019-08-27 09:48:02
categories: arXiv_CV
tags: arXiv_CV Detection
author: Artem Lukoyanov, Isabella Haberbosch, Constantin Pape, Alwin Kraemer, Yannick Schwab, Anna Kreshuk
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in high-throughput electron microscopy imaging enable detailed study of centrosome aberrations in cancer cells. While the image acquisition in such pipelines is automated, manual detection of centrioles is still necessary to select cells for re-imaging at higher magnification. In this contribution we propose an algorithm which performs this step automatically and with high accuracy. From the image labels produced by human experts and a 3D model of a centriole we construct an additional training set with patch-level labels. A two-level DenseNet is trained on the hybrid training data with synthetic patches and real images, achieving much better results on real patient data than training only at the image-level. The code can be found at https://github.com/kreshuklab/centriole_detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10109](http://arxiv.org/abs/1908.10109)

##### PDF
[http://arxiv.org/pdf/1908.10109](http://arxiv.org/pdf/1908.10109)

