---
layout: post
title: "A Pretrained DenseNet Encoder for Brain Tumor Segmentation"
date: 2018-11-19 08:00:22
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning
author: Jean Stawiaski
mathjax: true
---

* content
{:toc}

##### Abstract
This article presents a convolutional neural network for the automatic segmentation of brain tumors in multimodal 3D MR images based on a U-net architecture.We evaluate the use of a densely connected convolutional network encoder (DenseNet) which was pretrained on the ImageNet data set. We detail two network architectures that can take into account multiple 3D images as inputs. This work aims to identify if a generic pretrained network can be used for very specific medical applications where the target data differ both in the number of spatial dimensions as well as in the number of inputs channels. Moreover in order to regularize this transfer learning task we only train the decoder part of the U-net architecture. We evaluate the effectiveness of the proposed approach on the BRATS 2018 segmentation challenge where we obtained dice scores of 0.79, 0.90, 0.85 and 95/% Hausdorff distance of 2.9mm, 3.95mm, and 6.48mm for enhanced tumor core, whole tumor and tumor core respectively on the validation set. This scores degrades to 0.77, 0.88, 0.78 and 95 /% Hausdorff distance of 3.6mm, 5.72mm, and 5.83mm on the testing set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07542](http://arxiv.org/abs/1811.07542)

##### PDF
[http://arxiv.org/pdf/1811.07542](http://arxiv.org/pdf/1811.07542)

