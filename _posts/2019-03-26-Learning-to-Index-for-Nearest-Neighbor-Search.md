---
layout: post
title: "Learning to Index for Nearest Neighbor Search"
date: 2019-03-26 12:21:18
categories: arXiv_CV
tags: arXiv_CV Relation
author: Chih-Yi Chiu, Amorntip Prayoonwong, Yin-Chih Liao
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we present a novel ranking model based on learning neighborhood relationships embedded in the index space. Given a query point, conventional approximate nearest neighbor search calculates the distances to the cluster centroids, before ranking the clusters from near to far based on the distances. The data indexed in the top-ranked clusters are retrieved and treated as the nearest neighbor candidates for the query. However, the loss of quantization between the data and cluster centroids will inevitably harm the search accuracy. To address this problem, the proposed model ranks clusters based on their nearest neighbor probabilities rather than the query-centroid distances. The nearest neighbor probabilities are estimated by employing neural networks to characterize the neighborhood relationships, i.e., the density function of nearest neighbors with respect to the query. The proposed probability-based ranking can replace the conventional distance-based ranking for finding candidate clusters, and the predicted probability can be used to determine the data quantity to be retrieved from the candidate cluster. Our experimental results demonstrated that the proposed ranking model could boost the search performance effectively in billion-scale datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.02962](http://arxiv.org/abs/1807.02962)

##### PDF
[http://arxiv.org/pdf/1807.02962](http://arxiv.org/pdf/1807.02962)

