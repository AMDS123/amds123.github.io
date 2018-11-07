---
layout: post
title: "Leveraging Virtual and Real Person for Unsupervised Person Re-identification"
date: 2018-11-05 23:00:15
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Style_Transfer
author: Fengxiang Yang, Zhun Zhong, Zhiming Luo, Sheng Lian, Shaozi Li
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-ID) is a challenging problem especially when no labels are available for training. Although recent deep re-ID methods have achieved great improvement, it is still difficult to optimize deep re-ID model without annotations in training data. To address this problem, this study introduces a novel approach for unsupervised person re-ID by leveraging virtual and real data. Our approach includes two components: virtual person generation and training of deep re-ID model. For virtual person generation, we learn a person generation model and a camera style transfer model using unlabeled real data to generate virtual persons with different poses and camera styles. The virtual data is formed as labeled training data, enabling subsequently training deep re-ID model in supervision. For training of deep re-ID model, we divide it into three steps: 1) pre-training a coarse re-ID model by using virtual data; 2) collaborative filtering based positive pair mining from the real data; and 3) fine-tuning of the coarse re-ID model by leveraging the mined positive pairs and virtual data. The final re-ID model is achieved by iterating between step 2 and step 3 until convergence. Experimental results on two large-scale datasets, Market-1501 and DukeMTMC-reID, demonstrate the effectiveness of our approach and shows that the state of the art is achieved in unsupervised person re-ID.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02074](https://arxiv.org/abs/1811.02074)

##### PDF
[https://arxiv.org/pdf/1811.02074](https://arxiv.org/pdf/1811.02074)

