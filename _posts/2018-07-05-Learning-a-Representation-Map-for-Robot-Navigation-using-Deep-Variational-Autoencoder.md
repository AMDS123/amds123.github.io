---
layout: post
title: "Learning a Representation Map for Robot Navigation using Deep Variational Autoencoder"
date: 2018-07-05 14:46:32
categories: arXiv_CV
tags: arXiv_CV GAN
author: Kaixin Hu, Peter O&#x27;Connor
mathjax: true
---

* content
{:toc}

##### Abstract
The aim of this work is to use Variational Autoencoder (VAE) to learn a representation of an indoor environment that can be used for robot navigation. We use images extracted from a video, in which a camera takes a tour around a house, for training the VAE model with a 4 dimensional latent space. After the model is trained, each real frame has a corresponding representation point on manifold in the latent space, and each representation point has corresponding reconstructed image. For the navigation problem, we map the starting image and destination image to the latent space, then optimize a path on the learned manifold connecting the two points, and finally map the path back through decoder to a sequence of images. The ideal sequence of images should correspond to a route that is spatially continuous - i.e. neighbor images in the route should correspond to neighbor locations in physical space. Such a route could be used for navigation with computer vision techniques, i.e. a robot could follow the image sequence from starting location to destination in the environment step by step. We implement this algorithm, but find in our experimental results that the resulting route is not satisfactory. The route consist of several discontinuous image frames along the ideal routes, so that the route could not be followed by a robot with computer vision techniques in practice. In our evaluation, we propose two reasons for our failure to automatically find continuous routes: (1) The VAE tends to capture global structures, but discard the details; (2) the Euclidean similarity metric used for measuring continuity between house images is sub-optimal. For further work, we propose: trying other generative models like VAE-GANs which may be better at reconstructing the details to learn the representation map, and adjusting the similarity metric in the path selecting algorithm.

##### Abstract (translated by Google)
这项工作的目的是使用变分自动编码器（VAE）来学习可用于机器人导航的室内环境的表示。我们使用从视频中提取的图像，其中相机在房屋周围巡视，用于训练具有4维潜在空间的VAE模型。在训练模型之后，每个真实帧在潜在空间中的流形上具有对应的表示点，并且每个表示点具有对应的重建图像。对于导航问题，我们将起始图像和目标图像映射到潜在空间，然后优化连接两个点的学习流形上的路径，最后将路径通过解码器映射到一系列图像。理想的图像序列应该对应于空间连续的路线 - 即，路线中的相邻图像应该对应于物理空间中的相邻位置。这种路线可以用于利用计算机视觉技术进行导航，即机器人可以逐步跟随图像序列从环境中的起始位置到目的地。我们实现了这个算法，但在我们的实验结果中发现得到的路线并不令人满意。该路线由沿着理想路线的若干不连续图像帧组成，因此在实践中具有计算机视觉技术的机器人不能遵循该路线。在我们的评估中，我们提出了两个原因，即我们未能自动找到连续路线：（1）VAE倾向于捕捉全局结构，但丢弃细节; （2）用于测量房屋图像之间连续性的欧几里德相似性度量是次优的。对于进一步的工作，我们建议：尝试其他生成模型，如VAE-GAN，可能更好地重建细节以学习表示图，并调整路径选择算法中的相似性度量。

##### URL
[http://arxiv.org/abs/1807.02401](http://arxiv.org/abs/1807.02401)

##### PDF
[http://arxiv.org/pdf/1807.02401](http://arxiv.org/pdf/1807.02401)

