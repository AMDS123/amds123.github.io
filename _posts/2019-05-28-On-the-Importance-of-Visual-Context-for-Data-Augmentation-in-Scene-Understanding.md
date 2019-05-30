---
layout: post
title: "On the Importance of Visual Context for Data Augmentation in Scene Understanding"
date: 2019-05-28 14:25:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation CNN Detection Recognition
author: Nikita Dvornik, Julien Mairal, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Performing data augmentation for learning deep neural networks is known to be important for training visual recognition systems. By artificially increasing the number of training examples, it helps reducing overfitting and improves generalization. While simple image transformations can already improve predictive performance in most vision tasks, larger gains can be obtained by leveraging task-specific prior knowledge. In this work, we consider object detection, semantic and instance segmentation and augment the training images by blending objects in existing scenes, using instance segmentation annotations. We observe that randomly pasting objects on images hurts the performance, unless the object is placed in the right context. To resolve this issue, we propose an explicit context model by using a convolutional neural network, which predicts whether an image region is suitable for placing a given object or not. In our experiments, we show that our approach is able to improve object detection, semantic and instance segmentation on the PASCAL VOC12 and COCO datasets, with significant gains in a limited annotation scenario, i.e. when only one category is annotated. We also show that the method is not limited to datasets that come with expensive pixel-wise instance annotations and can be used when only bounding boxes are available, by employing weakly-supervised learning for instance masks approximation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.02492](http://arxiv.org/abs/1809.02492)

##### PDF
[http://arxiv.org/pdf/1809.02492](http://arxiv.org/pdf/1809.02492)

