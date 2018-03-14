---
layout: post
title: "Multi-Frame Quality Enhancement for Compressed Video"
date: 2018-03-13 08:40:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Ren Yang, Mai Xu, Zulin Wang, Tianyi Li
mathjax: true
---

* content
{:toc}

##### Abstract
The past few years have witnessed great success in applying deep learning to enhance the quality of compressed image/video. The existing approaches mainly focus on enhancing the quality of a single frame, ignoring the similarity between consecutive frames. In this paper, we investigate that heavy quality fluctuation exists across compressed video frames, and thus low quality frames can be enhanced using the neighboring high quality frames, seen as Multi-Frame Quality Enhancement (MFQE). Accordingly, this paper proposes an MFQE approach for compressed video, as a first attempt in this direction. In our approach, we firstly develop a Support Vector Machine (SVM) based detector to locate Peak Quality Frames (PQFs) in compressed video. Then, a novel Multi-Frame Convolutional Neural Network (MF-CNN) is designed to enhance the quality of compressed video, in which the non-PQF and its nearest two PQFs are as the input. The MF-CNN compensates motion between the non-PQF and PQFs through the Motion Compensation subnet (MC-subnet). Subsequently, the Quality Enhancement subnet (QE-subnet) reduces compression artifacts of the non-PQF with the help of its nearest PQFs. Finally, the experiments validate the effectiveness and generality of our MFQE approach in advancing the state-of-the-art quality enhancement of compressed video. The code of our MFQE approach is available at https://github.com/ryangBUAA/MFQE.git.

##### Abstract (translated by Google)
过去几年在应用深度学习提高压缩图像/视频质量方面取得了巨大成功。现有的方法主要集中在提高单个帧的质量，忽略连续帧之间的相似性。在本文中，我们研究了压缩视频帧之间存在较大的质量波动，因此可以使用相邻的高质量帧（即多帧质量增强（MFQE））来增强低质量帧。因此，本文提出了一种用于压缩视频的MFQE方法，作为此方向的第一次尝试。在我们的方法中，我们首先开发基于支持向量机（SVM）的检测器来定位压缩视频中的峰值质量帧（PQF）。然后，设计一种新颖的多帧卷积神经网络（MF-CNN）来提高压缩视频的质量，其中非PQF及其最近的两个PQF作为输入。 MF-CNN通过运动补偿子网（MC-subnet）补偿非PQF和PQF之间的运动。随后，质量增强子网（QE-subnet）借助最近的PQF来减少非PQF的压缩伪影。最后，这些实验验证了我们的MFQE方法在推进压缩视频的最新质量增强方面的有效性和一般性。我们的MFQE方法的代码可在https://github.com/ryangBUAA/MFQE.git获得。

##### URL
[http://arxiv.org/abs/1803.04680](http://arxiv.org/abs/1803.04680)

##### PDF
[http://arxiv.org/pdf/1803.04680](http://arxiv.org/pdf/1803.04680)

