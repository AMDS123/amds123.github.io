---
layout: post
title: "Bottleneck Supervised U-Net for Pixel-wise Liver and Tumor Segmentation"
date: 2018-10-16 13:02:57
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN
author: Song Li, Geoffrey Kwok Fai Tso
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) has been widely used for image processing tasks.In this paper we design a bottleneck supervised U-Net model and apply it to liver and tumor segmentation. Taking an image as input, the model outputs segmented images of the same size, each pixel of which takes value from 1 to K where K is the number of classes to be segmented. The innovations of this paper are two-fold: first we design a novel U-Net structure which include dense block and inception block as the base U-Net; second we design a double U-Net architecture based on the base U-Net and includes an encoding U-Net and a segmentation U-Net. The encoding U-Net is first trained to encode the labels, then the encodings are used to supervise the bottleneck of the segmentation U-Net. While training the segmentation U-Net, a weighted average of dice loss(for the final output) and MSE loss(for the bottleneck) is used as the overall loss function. This approach can help retain the hidden features of input images. The model is applied to a liver tumor 3D CT scan dataset to conduct liver and tumor segmentation sequentially. Experimental results indicate bottleneck supervised U-Net can accomplish segmentation tasks effectively with better performance in controlling shape distortion, reducing false positive and false negative, besides accelerating convergence. Besides, this model has good generalization for further improvement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10331](http://arxiv.org/abs/1810.10331)

##### PDF
[http://arxiv.org/pdf/1810.10331](http://arxiv.org/pdf/1810.10331)

