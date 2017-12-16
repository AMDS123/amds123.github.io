---
layout: post
title: "Unsupervised Domain Adaptation for Face Recognition in Unlabeled Videos"
date: 2017-08-07 16:36:54
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Face Recognition Face_Recognition
author: Kihyuk Sohn, Sifei Liu, Guangyu Zhong, Xiang Yu, Ming-Hsuan Yang, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Despite rapid advances in face recognition, there remains a clear gap between the performance of still image-based face recognition and video-based face recognition, due to the vast difference in visual quality between the domains and the difficulty of curating diverse large-scale video datasets. This paper addresses both of those challenges, through an image to video feature-level domain adaptation approach, to learn discriminative video frame representations. The framework utilizes large-scale unlabeled video data to reduce the gap between different domains while transferring discriminative knowledge from large-scale labeled still images. Given a face recognition network that is pretrained in the image domain, the adaptation is achieved by (i) distilling knowledge from the network to a video adaptation network through feature matching, (ii) performing feature restoration through synthetic data augmentation and (iii) learning a domain-invariant feature through a domain adversarial discriminator. We further improve performance through a discriminator-guided feature fusion that boosts high-quality frames while eliminating those degraded by video domain-specific factors. Experiments on the YouTube Faces and IJB-A datasets demonstrate that each module contributes to our feature-level domain adaptation framework and substantially improves video face recognition performance to achieve state-of-the-art accuracy. We demonstrate qualitatively that the network learns to suppress diverse artifacts in videos such as pose, illumination or occlusion without being explicitly trained for them.

##### Abstract (translated by Google)
尽管在人脸识别方面取得了快速的进展，但由于视觉质量与领域的视觉质量差异很大，难以管理各种大型视频，所以在基于静止图像的人脸识别和基于视频的人脸识别之间仍然存在明显的差距数据集。本文针对这两个挑战，通过图像到视频特征级别的领域适应方法，学习歧视性的视频帧表示。该框架利用大规模无标记的视频数据来减少不同领域之间的差距，同时将大规模标记的静止图像的识别性知识传递出去。 （i）通过特征匹配将知识从网络提取到视频自适应网络，（ii）通过合成数据增强执行特征恢复，以及（iii）学习在图像域中预先训练的人脸识别网络通过域对抗鉴别器的域不变特征。我们通过鉴别器引导的特征融合进一步提高性能，提高高质量帧，同时消除由视频领域特定因素降解的特征。 YouTube Faces和IJB-A数据集上的实验表明，每个模块都有助于我们的功能级域适应框架，并大大提高了视频人脸识别性能，实现了最新的准确性。我们从性质上证明，网络学习抑制视频中的不同文物，如姿势，照明或遮挡，而不需要对它们进行明确的训练。

##### URL
[https://arxiv.org/abs/1708.02191](https://arxiv.org/abs/1708.02191)

##### PDF
[https://arxiv.org/pdf/1708.02191](https://arxiv.org/pdf/1708.02191)

