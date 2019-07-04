---
layout: post
title: "SkeletonNet: Shape Pixel to Skeleton Pixel"
date: 2019-07-02 23:44:05
categories: arXiv_CV
tags: arXiv_CV GAN CNN Deep_Learning
author: Sabari Nathan, Priya Kansal
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning for Geometric Shape Understating has organized a challenge for extracting different kinds of skeletons from the images of different objects. This competition is organized in association with CVPR 2019. There are three different tracks of this competition. The present manuscript describes the method used to train the model for the dataset provided in the first track. The first track aims to extract skeleton pixels from the shape pixels of 89 different objects. For the purpose of extracting the skeleton, a U-net model which is comprised of an encoder-decoder structure has been used. In our proposed architecture, unlike the plain decoder in the traditional Unet, we have designed the decoder in the format of HED architecture, wherein we have introduced 4 side layers and fused them to one dilation convolutional layer to connect the broken links of the skeleton. Our proposed architecture achieved the F1 score of 0.77 on test data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01683](http://arxiv.org/abs/1907.01683)

##### PDF
[http://arxiv.org/pdf/1907.01683](http://arxiv.org/pdf/1907.01683)

