---
layout: post
title: "Amortized Inference and Learning in Latent Conditional Random Fields for Weakly-Supervised Semantic Image Segmentation"
date: 2017-05-03 06:02:32
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Face Inference
author: Gaurav Pandey, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional random fields (CRFs) are commonly employed as a post-processing tool for image segmentation tasks. The unary potentials of the CRF are often learnt independently by a classifier, thereby decoupling the inference in CRF from the training of classifier. Such a scheme works effectively, when pixel-level labelling is available for all the images. However, in absence of pixel-level labels, the classifier is faced with the uphill task of selectively assigning the image-level labels to the pixels of the image. Prior work often relied on localization cues, such as saliency maps, objectness priors, bounding boxes etc., to address this challenging problem. In contrast, we model the labels of the pixels as latent variables of a CRF. The pixels and the image-level labels are the observed variables of the latent CRF. We amortize the cost of inference in the latent CRF over the entire dataset, by training an inference network to approximate the posterior distribution of the latent variables given the observed variables. The inference network can be trained in an end-to-end fashion, and requires no localization cues for training. Moreover, unlike other approaches for weakly-supervised segmentation, the proposed model doesn't require further post-processing. The proposed model achieves performance comparable with other approaches that employ saliency masks for the task of weakly-supervised semantic image segmentation on the challenging VOC 2012 dataset.

##### Abstract (translated by Google)
条件随机场（CRF）通常被用作图像分割任务的后处理工具。 CRF的一元化潜能通常由分类器独立学习，从而将CRF中的推理与分类器的训练分离开来。当像素级标签可用于所有图像时，这种方案可以有效地工作。然而，在没有像素级标签的情况下，分类器面临着有选择地将图像级标签分配给图像像素的艰巨任务。以前的工作往往依靠本地化的线索，如显着图，对象先验，边界框等，来解决这个具有挑战性的问题。相反，我们将像素的标签建模为CRF的潜在变量。像素和图像级标签是潜在CRF的观察变量。我们通过训练一个推理网络来推断潜在变量的后验分布，从而在整个数据集上分摊潜在变量的推理成本。推理网络可以以端到端的方式进行训练，并且不需要用于训练的定位线索。而且，与其他弱监督分割方法不同，所提出的模型不需要进一步的后处理。所提出的模型实现了与其他方法相比的性能，所述方法使用显着性掩模用于在具有挑战性的VOC 2012数据集上进行弱监督语义图像分割的任务。

##### URL
[https://arxiv.org/abs/1705.01262](https://arxiv.org/abs/1705.01262)

##### PDF
[https://arxiv.org/pdf/1705.01262](https://arxiv.org/pdf/1705.01262)

