---
layout: post
title: "Applying Faster R-CNN for Object Detection on Malaria Images"
date: 2019-03-11 16:14:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN CNN Classification Deep_Learning Detection
author: Jane Hung, Deepali Ravel, Stefanie C.P. Lopes, Gabriel Rangel, Odailton Amaral Nery, Benoit Malleret, Francois Nosten, Marcus V. G. Lacerda, Marcelo U. Ferreira, Laurent R&#xe9;nia, Manoj T. Duraisingh, Fabio T. M. Costa, Matthias Marti, Anne E. Carpenter
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based models have had great success in object detection, but the state of the art models have not yet been widely applied to biological image data. We apply for the first time an object detection model previously used on natural images to identify cells and recognize their stages in brightfield microscopy images of malaria-infected blood. Many micro-organisms like malaria parasites are still studied by expert manual inspection and hand counting. This type of object detection task is challenging due to factors like variations in cell shape, density, and color, and uncertainty of some cell classes. In addition, annotated data useful for training is scarce, and the class distribution is inherently highly imbalanced due to the dominance of uninfected red blood cells. We use Faster Region-based Convolutional Neural Network (Faster R-CNN), one of the top performing object detection models in recent years, pre-trained on ImageNet but fine tuned with our data, and compare it to a baseline, which is based on a traditional approach consisting of cell segmentation, extraction of several single-cell features, and classification using random forests. To conduct our initial study, we collect and label a dataset of 1300 fields of view consisting of around 100,000 individual cells. We demonstrate that Faster R-CNN outperforms our baseline and put the results in context of human performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.09548](http://arxiv.org/abs/1804.09548)

##### PDF
[http://arxiv.org/pdf/1804.09548](http://arxiv.org/pdf/1804.09548)

