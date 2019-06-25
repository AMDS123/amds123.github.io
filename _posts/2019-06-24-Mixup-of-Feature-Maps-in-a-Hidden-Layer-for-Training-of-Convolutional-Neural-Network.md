---
layout: post
title: "Mixup of Feature Maps in a Hidden Layer for Training of Convolutional Neural Network"
date: 2019-06-24 06:10:17
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Hideki Oki, Takio Kurita
mathjax: true
---

* content
{:toc}

##### Abstract
The deep Convolutional Neural Network (CNN) became very popular as a fundamental technique for image classification and objects recognition. To improve the recognition accuracy for the more complex tasks, deeper networks have being introduced. However, the recognition accuracy of the trained deep CNN drastically decreases for the samples which are obtained from the outside regions of the training samples. To improve the generalization ability for such samples, Krizhevsky et al. proposed to generate additional samples through transformations from the existing samples and to make the training samples richer. This method is known as data augmentation. Hongyi Zhang et al. introduced data augmentation method called mixup which achieves state-of-the-art performance in various datasets. Mixup generates new samples by mixing two different training samples. Mixing of the two images is implemented with simple image morphing. In this paper, we propose to apply mixup to the feature maps in a hidden layer. To implement the mixup in the hidden layer we use the Siamese network or the triplet network architecture to mix feature maps. From the experimental comparison, it is observed that the mixup of the feature maps obtained from the first convolution layer is more effective than the original image mixup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09739](http://arxiv.org/abs/1906.09739)

##### PDF
[http://arxiv.org/pdf/1906.09739](http://arxiv.org/pdf/1906.09739)

