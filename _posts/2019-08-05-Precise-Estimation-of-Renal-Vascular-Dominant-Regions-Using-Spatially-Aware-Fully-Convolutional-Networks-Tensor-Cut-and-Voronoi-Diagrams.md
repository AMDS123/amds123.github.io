---
layout: post
title: "Precise Estimation of Renal Vascular Dominant Regions Using Spatially Aware Fully Convolutional Networks, Tensor-Cut and Voronoi Diagrams"
date: 2019-08-05 10:11:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Chenglong Wang, Holger R. Roth, Takayuki Kitasaka, Masahiro Oda, Yuichiro Hayashi, Yasushi Yoshino, Tokunori Yamamoto, Naoto Sassa, Momokazu Goto, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new approach for precisely estimating the renal vascular dominant region using a Voronoi diagram. To provide computer-assisted diagnostics for the pre-surgical simulation of partial nephrectomy surgery, we must obtain information on the renal arteries and the renal vascular dominant regions. We propose a fully automatic segmentation method that combines a neural network and tensor-based graph-cut methods to precisely extract the kidney and renal arteries. First, we use a convolutional neural network to localize the kidney regions and extract tiny renal arteries with a tensor-based graph-cut method. Then we generate a Voronoi diagram to estimate the renal vascular dominant regions based on the segmented kidney and renal arteries. The accuracy of kidney segmentation in 27 cases with 8-fold cross validation reached a Dice score of 95%. The accuracy of renal artery segmentation in 8 cases obtained a centerline overlap ratio of 80%. Each partition region corresponds to a renal vascular dominant region. The final dominant-region estimation accuracy achieved a Dice coefficient of 80%. A clinical application showed the potential of our proposed estimation approach in a real clinical surgical environment. Further validation using large-scale database is our future work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01543](http://arxiv.org/abs/1908.01543)

##### PDF
[http://arxiv.org/pdf/1908.01543](http://arxiv.org/pdf/1908.01543)

