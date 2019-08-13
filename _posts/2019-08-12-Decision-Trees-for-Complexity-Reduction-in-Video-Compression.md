---
layout: post
title: "Decision Trees for Complexity Reduction in Video Compression"
date: 2019-08-12 14:27:16
categories: arXiv_CV
tags: arXiv_CV
author: Natasha Westland, André Seixas Dias, Marta Mrak
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method for complexity reduction in practical video encoders using multiple decision tree classifiers. The method is demonstrated for the fast implementation of the 'High Efficiency Video Coding' (HEVC) standard, chosen because of its high bit rate reduction capability but large complexity overhead. Optimal partitioning of each video frame into coding units (CUs) is the main source of complexity as a vast number of combinations are tested. The decision tree models were trained to identify when the CU testing process, a time-consuming Lagrangian optimisation, can be skipped i.e a high probability that the CU can remain whole. A novel approach to finding the simplest and most effective decision tree model called 'manual pruning' is described. Implementing the skip criteria reduced the average encoding time by 42.1% for a Bjøntegaard Delta rate detriment of 0.7%, for 17 standard test sequences in a range of resolutions and quantisation parameters.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.04168](https://arxiv.org/abs/1908.04168)

##### PDF
[https://arxiv.org/pdf/1908.04168](https://arxiv.org/pdf/1908.04168)

