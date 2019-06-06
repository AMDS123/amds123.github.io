---
layout: post
title: "A GLCM Embedded CNN Strategy for Computer-aided Diagnosis in Intracerebral Hemorrhage"
date: 2019-06-05 14:12:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Classification
author: Yifan Hu, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Computer-aided diagnosis (CADx) systems have been shown to assist radiologists by providing classifications of all kinds of medical images like Computed tomography (CT) and Magnetic resonance (MR). Currently, convolutional neural networks play an important role in CADx. However, since CNN model should have a square-like input, it is usually difficult to directly apply the CNN algorithms on the irregular segmentation region of interests (ROIs) where the radiologists are interested in. In this paper, we propose a new approach to construct the model by extracting and converting the information of the irregular region into a fixed-size Gray-Level Co-Occurrence Matrix (GLCM) and then utilize the GLCM as one input of our CNN model. In this way, as an useful implementary to the original CNN, a couple of GLCM-based features are also extracted by CNN. Meanwhile, the network will pay more attention to the important lesion area and achieve a higher accuracy in classification. Experiments are performed on three classification databases: Hemorrhage, BraTS18 and Cervix to validate the universality of our innovative model. In conclusion, the proposed framework outperforms the corresponding state-of-art algorithms on each database with both test losses and classification accuracy as the evaluation criteria.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02040](http://arxiv.org/abs/1906.02040)

##### PDF
[http://arxiv.org/pdf/1906.02040](http://arxiv.org/pdf/1906.02040)

