---
layout: post
title: "Batch-Shaped Channel Gated Networks"
date: 2019-07-15 17:58:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Inference Classification
author: Babak Ehteshami Bejnordi, Tijmen Blankevoort, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for gating deep-learning architectures on a fine-grained level. Individual convolutional maps are turned on/off conditionally on features in the network. This method allows us to train neural networks with a large capacity, but lower inference time than the full network. To achieve this, we introduce a new residual block architecture that gates convolutional channels in a fine-grained manner. We also introduce a generally applicable tool "batch-shaping" that matches the marginal aggregate posteriors of features in a neural network to a pre-specified prior distribution. We use this novel technique to force gates to be more conditional on the data. We present results on CIFAR-10 and ImageNet datasets for image classification and Cityscapes for semantic segmentation. Our results show that our method can slim down large architectures conditionally, such that the average computational cost on the data is on par with a smaller architecture, but with higher accuracy. In particular, our ResNet34 gated network achieves a performance of 72.55% top-1 accuracy compared to the 69.76% accuracy of the baseline ResNet18 model, for similar complexity. We also show that the resulting networks automatically learn to use more features for difficult examples and fewer features for simple examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06627](http://arxiv.org/abs/1907.06627)

##### PDF
[http://arxiv.org/pdf/1907.06627](http://arxiv.org/pdf/1907.06627)

