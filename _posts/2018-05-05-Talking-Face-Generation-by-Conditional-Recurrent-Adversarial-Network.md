---
layout: post
title: "Talking Face Generation by Conditional Recurrent Adversarial Network"
date: 2018-05-05 21:29:05
categories: arXiv_CV
tags: arXiv_CV Adversarial Face
author: Yang Song, Jingwen Zhu, Xiaolong Wang, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Given an arbitrary face image and an arbitrary speech clip, the proposed work attempts to generating the talking face video with accurate lip synchronization while maintaining smooth transition of both lip and facial movement over the entire video clip. Existing works either do not consider temporal dependency on face images across different video frames thus easily yielding noticeable/abrupt facial and lip movement or are only limited to the generation of talking face video for a specific person thus lacking generalization capacity. We propose a novel conditional video generation network where the audio input is treated as a condition for the recurrent adversarial network such that temporal dependency is incorporated to realize smooth transition for the lip and facial movement. In addition, we deploy a multi-task adversarial training scheme in the context of video generation to improve both photo-realism and the accuracy for lip synchronization. Finally, based on the phoneme distribution information extracted from the audio clip, we develop a sample selection method that effectively reduces the size of the training dataset without sacrificing the quality of the generated video. Extensive experiments on both controlled and uncontrolled datasets demonstrate the superiority of the proposed approach in terms of visual quality, lip sync accuracy, and smooth transition of lip and facial movement, as compared to the state-of-the-art.

##### Abstract (translated by Google)
鉴于任意人脸图像和任意语音剪辑，所提出的工作尝试生成具有准确唇部同步的讲话人脸视频，同时保持唇部和面部移动在整个视频剪辑上的平滑过渡。现有作品要么不考虑对不同视频帧中的脸部图像的时间依赖性，从而容易产生明显/突然的面部和唇部运动，或者仅限于针对特定人员的谈话面部视频的产生，因此缺乏泛化能力。我们提出了一种新的条件视频生成网络，其中音频输入被视为经常性对抗网络的条件，使得时间依赖性被结合以实现唇部和面部运动的平滑过渡。此外，我们在视频生成的环境中部署了多任务对抗训练方案，以改善照片真实感和嘴唇同步的准确性。最后，根据从音频剪辑中提取的音素发布信息，我们开发了一种样本选择方法，可以在不牺牲生成视频质量的情况下有效缩小训练数据集的大小。与最先进的技术相比，在控制和非控制数据集上进行的大量实验证明了所提出的方法在视觉质量，唇部同步精度以及唇部和面部运动的平滑过渡方面的优越性。

##### URL
[http://arxiv.org/abs/1804.04786](http://arxiv.org/abs/1804.04786)

##### PDF
[http://arxiv.org/pdf/1804.04786](http://arxiv.org/pdf/1804.04786)

