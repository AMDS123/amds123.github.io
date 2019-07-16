---
layout: post
title: "ThirdEye: Triplet Based Iris Recognition without Normalization"
date: 2019-07-13 23:27:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Recognition
author: Sohaib Ahmad, Benjamin Fuller
mathjax: true
---

* content
{:toc}

##### Abstract
Most iris recognition pipelines involve three stages: segmenting into iris/non-iris pixels, normalization the iris region to a fixed area, and extracting relevant features for comparison. Given recent advances in deep learning it is prudent to ask which stages are required for accurate iris recognition. Lojez et al. (IWBF 2019) recently concluded that the segmentation stage is still crucial for good accuracy.We ask if normalization is beneficial? Towards answering this question, we develop a new iris recognition system called ThirdEye based on triplet convolutional neural networks (Schroff et al., ICCV 2015). ThirdEye directly uses segmented images without normalization. We observe equal error rates of 1.32%, 9.20%, and 0.59% on the ND-0405, UbirisV2, and IITD datasets respectively. For IITD, the most constrained dataset, this improves on the best prior work. However, for ND-0405 and UbirisV2,our equal error rate is slightly worse than prior systems. Our concluding hypothesis is that normalization is more important for less constrained environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06147](http://arxiv.org/abs/1907.06147)

##### PDF
[http://arxiv.org/pdf/1907.06147](http://arxiv.org/pdf/1907.06147)

