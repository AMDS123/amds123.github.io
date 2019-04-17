---
layout: post
title: "Disentangling Pose from Appearance in Monochrome Hand Images"
date: 2019-04-16 08:15:26
categories: arXiv_AI
tags: arXiv_AI Pose_Estimation
author: Yikang Li, Chris Twigg, Yuting Ye, Lingling Tao, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Hand pose estimation from the monocular 2D image is challenging due to the variation in lighting, appearance, and background. While some success has been achieved using deep neural networks, they typically require collecting a large dataset that adequately samples all the axes of variation of hand images. It would, therefore, be useful to find a representation of hand pose which is independent of the image appearance~(like hand texture, lighting, background), so that we can synthesize unseen images by mixing pose-appearance combinations. In this paper, we present a novel technique that disentangles the representation of pose from a complementary appearance factor in 2D monochrome images. We supervise this disentanglement process using a network that learns to generate images of hand using specified pose+appearance features. Unlike previous work, we do not require image pairs with a matching pose; instead, we use the pose annotations already available and introduce a novel use of cycle consistency to ensure orthogonality between the factors. Experimental results show that our self-disentanglement scheme successfully decomposes the hand image into the pose and its complementary appearance features of comparable quality as the method using paired data. Additionally, training the model with extra synthesized images with unseen hand-appearance combinations by re-mixing pose and appearance factors from different images can improve the 2D pose estimation performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07528](http://arxiv.org/abs/1904.07528)

##### PDF
[http://arxiv.org/pdf/1904.07528](http://arxiv.org/pdf/1904.07528)

