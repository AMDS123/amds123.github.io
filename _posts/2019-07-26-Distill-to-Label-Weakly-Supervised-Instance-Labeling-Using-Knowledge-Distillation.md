---
layout: post
title: "Distill-to-Label: Weakly Supervised Instance Labeling Using Knowledge Distillation"
date: 2019-07-26 04:39:17
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Knowledge Segmentation Weakly_Supervised Classification Prediction Detection
author: Jayaraman J. Thiagarajan, Satyananda Kashyap, Alexandros Karagyris
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised instance labeling using only image-level labels, in lieu of expensive fine-grained pixel annotations, is crucial in several applications including medical image analysis. In contrast to conventional instance segmentation scenarios in computer vision, the problems that we consider are characterized by a small number of training images and non-local patterns that lead to the diagnosis. In this paper, we explore the use of multiple instance learning (MIL) to design an instance label generator under this weakly supervised setting. Motivated by the observation that an MIL model can handle bags of varying sizes, we propose to repurpose an MIL model originally trained for bag-level classification to produce reliable predictions for single instances, i.e., bags of size $1$. To this end, we introduce a novel regularization strategy based on virtual adversarial training for improving MIL training, and subsequently develop a knowledge distillation technique for repurposing the trained MIL model. Using empirical studies on colon cancer and breast cancer detection from histopathological images, we show that the proposed approach produces high-quality instance-level prediction and significantly outperforms state-of-the MIL methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12926](http://arxiv.org/abs/1907.12926)

##### PDF
[http://arxiv.org/pdf/1907.12926](http://arxiv.org/pdf/1907.12926)

