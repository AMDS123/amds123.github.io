---
layout: post
title: "Breast Ultrasound Computer-Aided Diagnosis Using Structure-Aware Triplet Path Networks"
date: 2019-08-09 20:36:40
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Prediction
author: Erlei Zhang, Zi Yang, Stephen Seiler, Mingli Chen, Weiguo Lu, Xuejun Gu
mathjax: true
---

* content
{:toc}

##### Abstract
Breast ultrasound (US) is an effective imaging modality for breast cancer detec-tion and diagnosis. The structural characteristics of breast lesion play an im-portant role in Computer-Aided Diagnosis (CAD). In this paper, a novel struc-ture-aware triplet path networks (SATPN) was designed to integrate classifica-tion and two image reconstruction tasks to achieve accurate diagnosis on US im-ages with small training dataset. Specifically, we enhance clinically-approved breast lesion structure characteristics though converting original breast US imag-es to BIRADS-oriented feature maps (BFMs) with a distance-transformation coupled Gaussian filter. Then, the converted BFMs were used as the inputs of SATPN, which performed lesion classification task and two unsupervised stacked convolutional Auto-Encoder (SCAE) networks for benign and malignant image reconstruction tasks, independently. We trained the SATPN with an alter-native learning strategy by balancing image reconstruction error and classification label prediction error. At the test stage, the lesion label was determined by the weighted voting with reconstruction error and label prediction error. We com-pared the performance of the SATPN with TPN using original image as input and our previous developed semi-supervised deep learning methods using BFMs as inputs. Experimental results on two breast US datasets showed that SATPN ranked the best among the three networks, with classification accuracy around 93.5%. These findings indicated that SATPN is promising for effective breast US lesion CAD using small datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09825](http://arxiv.org/abs/1908.09825)

##### PDF
[http://arxiv.org/pdf/1908.09825](http://arxiv.org/pdf/1908.09825)

