---
layout: post
title: "Omnidirectional CNN for Visual Place Recognition and Navigation"
date: 2018-03-12 12:49:50
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Recognition
author: Tsun-Hsuan Wang, Hung-Jui Huang, Juan-Ting Lin, Chan-Wei Hu, Kuo-Hao Zeng, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
$ $Visual place recognition is challenging, especially when only a few place exemplars are given. To mitigate the challenge, we consider place recognition method using omnidirectional cameras and propose a novel Omnidirectional Convolutional Neural Network (O-CNN) to handle severe camera pose variation. Given a visual input, the task of the O-CNN is not to retrieve the matched place exemplar, but to retrieve the closest place exemplar and estimate the relative distance between the input and the closest place. With the ability to estimate relative distance, a heuristic policy is proposed to navigate a robot to the retrieved closest place. Note that the network is designed to take advantage of the omnidirectional view by incorporating circular padding and rotation invariance. To train a powerful O-CNN, we build a virtual world for training on a large scale. We also propose a continuous lifted structured feature embedding loss to learn the concept of distance efficiently. Finally, our experimental results confirm that our method achieves state-of-the-art accuracy and speed with both the virtual world and real-world datasets.

##### Abstract (translated by Google)
$ $视觉地点识别具有挑战性，特别是在仅给出几个地方范例时。为了缓解这一挑战，我们考虑使用全向摄像头的地点识别方法，并提出了一种新颖的全向卷积神经网络（O-CNN）来处理严重的相机姿态变化。给定视觉输入，O-CNN的任务不是检索匹配的地点范例，而是检索最接近的地点范例并估计输入与最近地点之间的相对距离。利用估计相对距离的能力，提出了启发式策略来将机器人导航到检索到的最近位置。请注意，该网络旨在通过引入圆形填充和旋转不变性来充分利用全方位视图。为了训练强大的O-CNN，我们建立了一个大规模培训的虚拟世界。我们还提出了一种连续提升的结构化特征嵌入损失，以有效地学习距离概念。最后，我们的实验结果证实，我们的方法能够在虚拟世界和真实世界的数据集中实现最先进的准确性和速度。

##### URL
[https://arxiv.org/abs/1803.04228](https://arxiv.org/abs/1803.04228)

##### PDF
[https://arxiv.org/pdf/1803.04228](https://arxiv.org/pdf/1803.04228)

