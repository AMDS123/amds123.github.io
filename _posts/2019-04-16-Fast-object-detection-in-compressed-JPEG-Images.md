---
layout: post
title: "Fast object detection in compressed JPEG Images"
date: 2019-04-16 22:10:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Attention CNN Deep_Learning Detection
author: Benjamin Deguerre, Cl&#xe9;ment Chatelain, Gilles Gasso
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in still images has drawn a lot of attention over past few years, and with the advent of Deep Learning impressive performances have been achieved with numerous industrial applications. Most of these deep learning models rely on RGB images to localize and identify objects in the image. However in some application scenarii, images are compressed either for storage savings or fast transmission. Therefore a time consuming image decompression step is compulsory in order to apply the aforementioned deep models. To alleviate this drawback, we propose a fast deep architecture for object detection in JPEG images, one of the most widespread compression format. We train a neural network to detect objects based on the blockwise DCT (discrete cosine transform) coefficients {issued from} the JPEG compression algorithm. We modify the well-known Single Shot multibox Detector (SSD) by replacing its first layers with one convolutional layer dedicated to process the DCT inputs. Experimental evaluations on PASCAL VOC and industrial dataset comprising images of road traffic surveillance show that the model is about $2\times$ faster than regular SSD with promising detection performances. To the best of our knowledge, this paper is the first to address detection in compressed JPEG images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08408](http://arxiv.org/abs/1904.08408)

##### PDF
[http://arxiv.org/pdf/1904.08408](http://arxiv.org/pdf/1904.08408)

