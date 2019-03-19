---
layout: post
title: "Patch Clustering for Representation of Histopathology Images"
date: 2019-03-17 01:40:45
categories: arXiv_CV
tags: arXiv_CV GAN
author: Wafa Chenni, Habib Herbi, Morteza Babaie, H.R.Tizhoosh
mathjax: true
---

* content
{:toc}

##### Abstract
Whole Slide Imaging (WSI) has become an important topic during the last decade. Even though significant progress in both medical image processing and computational resources has been achieved, there are still problems in WSI that need to be solved. A major challenge is the scan size. The dimensions of digitized tissue samples may exceed 100,000 by 100,000 pixels causing memory and efficiency obstacles for real-time processing. The main contribution of this work is representing a WSI by selecting a small number of patches for algorithmic processing (e.g., indexing and search). As a result, we reduced the search time and storage by various factors between ($50\% - 90\%$), while losing only a few percentages in the patch retrieval accuracy. A self-organizing map (SOM) has been applied on local binary patterns (LBP) and deep features of the KimiaPath24 dataset in order to cluster patches that share the same characteristics. We used a Gaussian mixture model (GMM) to represent each class with a rather small ($10\%-50\%$) portion of patches. The results showed that LBP features can outperform deep features. By selecting only $50\%$ of all patches after SOM clustering and GMM patch selection, we received $65\%$ accuracy for retrieval of the best match, while the maximum accuracy (using all patches) was $69\%$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07013](http://arxiv.org/abs/1903.07013)

##### PDF
[http://arxiv.org/pdf/1903.07013](http://arxiv.org/pdf/1903.07013)

