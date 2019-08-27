---
layout: post
title: "Plexus Convolutional Neural Network : A novel neural network architecture for histologic image analysis"
date: 2019-08-24 01:29:34
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Okyaz Eminaga, Mahmoud Abbas, Christian Kunder, Andreas M. Loening, Jeanne Shen, James D. Brooks, Curtis P. Langlotz, Daniel L. Rubin
mathjax: true
---

* content
{:toc}

##### Abstract
Different convolutional neural network (CNN) models have been tested for their application in histologic imaging analyses. However, these models are prone to overfitting due to their large parameter capacity, requiring more data and expensive computational resources for model training. Given these limitations, we developed and tested PlexusNet for histologic evaluation using a single GPU by a batch dimension of 16x512x512x3. We utilized 62 Hematoxylin and eosin stain (H&amp;E) annotated histological images of radical prostatectomy cases from TCGA-PRAD and Stanford University, and 24 H&amp;E whole-slide images with hepatocellular carcinoma from TCGA-LIHC diagnostic histology images. Base models were DenseNet, Inception V3, and MobileNet and compared with PlexusNet. The dice coefficient (DSC) was evaluated for each model. PlexusNet delivered comparable classification performance (DSC at patch level: 0.89) for H&amp;E whole-slice images in distinguishing prostate cancer from normal tissues. The parameter capacity of PlexusNet is 9 times smaller than MobileNet or 58 times smaller than Inception V3, respectively. Similar findings were observed in distinguishing hepatocellular carcinoma from non-cancerous liver histologies (DSC at patch level: 0.85). As conclusion, PlexusNet represents a novel model architecture for histological image analysis that achieves classification performance comparable to the base models while providing orders-of-magnitude memory savings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09067](http://arxiv.org/abs/1908.09067)

##### PDF
[http://arxiv.org/pdf/1908.09067](http://arxiv.org/pdf/1908.09067)

