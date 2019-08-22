---
layout: post
title: "Semantic-Transferable Weakly-Supervised Endoscopic Lesions Segmentation"
date: 2019-08-21 01:50:44
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation Semantic_Segmentation
author: Jiahua Dong, Yang Cong, Gan Sun, Dongdong Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised learning under image-level labels supervision has been widely applied to semantic segmentation of medical lesions regions. However, 1) most existing models rely on effective constraints to explore the internal representation of lesions, which only produces inaccurate and coarse lesions regions; 2) they ignore the strong probabilistic dependencies between target lesions dataset (e.g., enteroscopy images) and well-to-annotated source diseases dataset (e.g., gastroscope images). To better utilize these dependencies, we present a new semantic lesions representation transfer model for weakly-supervised endoscopic lesions segmentation, which can exploit useful knowledge from relevant fully-labeled diseases segmentation task to enhance the performance of target weakly-labeled lesions segmentation task. More specifically, a pseudo label generator is proposed to leverage seed information to generate highly-confident pseudo pixel labels by incorporating class balance and super-pixel spatial prior. It can iteratively include more hard-to-transfer samples from weakly-labeled target dataset into training set. Afterwards, dynamically searched feature centroids for same class among different datasets are aligned by accumulating previously-learned features. Meanwhile, adversarial learning is also employed in this paper, to narrow the gap between the lesions among different datasets in output space. Finally, we build a new medical endoscopic dataset with 3659 images collected from more than 1100 volunteers. Extensive experiments on our collected dataset and several benchmark datasets validate the effectiveness of our model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07669](http://arxiv.org/abs/1908.07669)

##### PDF
[http://arxiv.org/pdf/1908.07669](http://arxiv.org/pdf/1908.07669)

