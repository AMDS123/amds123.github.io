---
layout: post
title: "Sparse Label Smoothing Regularization for Person Re-Identification"
date: 2019-03-05 06:50:44
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Adversarial Sparse Person_Re-identification Deep_Learning
author: Jean-Paul Ainam, Ke Qin, Guisong Liu, Guangchun Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) is a cross-camera retrieval task which establishes a correspondence between images of a person from multiple cameras. Deep Learning methods have been successfully applied to this problem and have achieved impressive results. However, these methods require a large amount of labeled training data. Currently labeled datasets in person re-id are limited in their scale and manual acquisition of such large-scale datasets from surveillance cameras is a tedious and labor-intensive task. In this paper, we propose a framework that performs intelligent data augmentation and assigns partial smoothing label to generated data. Our approach first exploits the clustering property of existing person re-id datasets to create groups of similar objects that model cross-view variations. Each group is then used to generate realistic images through adversarial training. Our aim is to emphasize feature similarity between generated samples and the original samples. Finally, we assign a non-uniform label distribution to the generated samples and define a regularized loss function for training. The proposed approach tackles two problems (1) how to efficiently use the generated data and (2) how to address the over-smoothness problem found in current regularization methods. Extensive experiments on four larges cale datasets show that our regularization method significantly improves the Re-ID accuracy compared to existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.04976](http://arxiv.org/abs/1809.04976)

##### PDF
[http://arxiv.org/pdf/1809.04976](http://arxiv.org/pdf/1809.04976)

