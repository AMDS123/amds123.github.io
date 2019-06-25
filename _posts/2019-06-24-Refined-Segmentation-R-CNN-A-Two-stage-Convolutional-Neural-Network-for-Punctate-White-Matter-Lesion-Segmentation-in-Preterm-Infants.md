---
layout: post
title: "Refined-Segmentation R-CNN: A Two-stage Convolutional Neural Network for Punctate White Matter Lesion Segmentation in Preterm Infants"
date: 2019-06-24 01:19:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Yalong Liu, Jie Li, Ying Wang, Miaomiao Wang, Fan Wu, Zhicheng Jiao, Jian Yang, Xingbo Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of punctate white matter lesion (PWML) in infantile brains by an automatic algorithm can reduce the potential risk of postnatal development. How to segment PWML effectively has become one of the active topics in medical image segmentation in recent years. In this paper, we construct an efficient two-stage PWML semantic segmentation network based on the characteristics of the lesion, called refined segmentation R-CNN (RS RCNN). We propose a heuristic RPN (H-RPN) which can utilize surrounding information around the PWMLs for heuristic segmentation. Also, we design a lightweight segmentation network to segment the lesion in a fast way. Densely connected conditional random field (DCRF) is used to optimize the segmentation results. We only use T1w MRIs to segment PWMLs. The result shows that our model can well segment the lesion of ordinary size or even pixel size. The Dice similarity coefficient reaches 0.6616, the sensitivity is 0.7069, the specificity is 0.9997, and the Hausdorff distance is 52.9130. The proposed method outperforms the state-of-the-art algorithm. (The code of this paper is available on https://github.com/YalongLiu/Refined-Segmentation-R-CNN)

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09684](http://arxiv.org/abs/1906.09684)

##### PDF
[http://arxiv.org/pdf/1906.09684](http://arxiv.org/pdf/1906.09684)

