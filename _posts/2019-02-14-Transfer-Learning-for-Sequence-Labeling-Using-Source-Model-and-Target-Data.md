---
layout: post
title: "Transfer Learning for Sequence Labeling Using Source Model and Target Data"
date: 2019-02-14 11:40:58
categories: arXiv_CL
tags: arXiv_CL Knowledge Transfer_Learning Recognition
author: Lingzhen Chen, Alessandro Moschitti
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an approach for transferring the knowledge of a neural model for sequence labeling, learned from the source domain, to a new model trained on a target domain, where new label categories appear. Our transfer learning (TL) techniques enable to adapt the source model using the target data and new categories, without accessing to the source data. Our solution consists in adding new neurons in the output layer of the target model and transferring parameters from the source model, which are then fine-tuned with the target data. Additionally, we propose a neural adapter to learn the difference between the source and the target label distribution, which provides additional important information to the target model. Our experiments on Named Entity Recognition show that (i) the learned knowledge in the source model can be effectively transferred when the target data contains new categories and (ii) our neural adapter further improves such transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05309](http://arxiv.org/abs/1902.05309)

##### PDF
[http://arxiv.org/pdf/1902.05309](http://arxiv.org/pdf/1902.05309)

