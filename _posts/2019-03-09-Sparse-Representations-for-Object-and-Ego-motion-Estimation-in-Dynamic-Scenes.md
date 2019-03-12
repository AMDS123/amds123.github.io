---
layout: post
title: "Sparse Representations for Object and Ego-motion Estimation in Dynamic Scenes"
date: 2019-03-09 03:56:53
categories: arXiv_CV
tags: arXiv_CV Sparse Prediction
author: Hirak J Kashyap, Charless Fowlkes, Jeffrey L Krichmar
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic scenes that contain both object motion and egomotion are a challenge for monocular visual odometry (VO). Another issue with monocular VO is the scale ambiguity, i.e. these methods cannot estimate scene depth and camera motion in real scale. Here, we propose a learning based approach to predict camera motion parameters directly from optic flow, by marginalizing depthmap variations and outliers. This is achieved by learning a sparse overcomplete basis set of egomotion in an autoencoder network, which is able to eliminate irrelevant components of optic flow for the task of camera parameter or motionfield estimation. The model is trained using a sparsity regularizer and a supervised egomotion loss, and achieves the state-of-the-art performances on trajectory prediction and camera rotation prediction tasks on KITTI and Virtual KITTI datasets, respectively. The sparse latent space egomotion representation learned by the model is robust and requires only 5% of the hidden layer neurons to maintain the best trajectory prediction accuracy on KITTI dataset. Additionally, in presence of depth information, the proposed method demonstrates faithful object velocity prediction for wide range of object sizes and speeds by global compensation of predicted egomotion and a divisive normalization procedure.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03731](https://arxiv.org/abs/1903.03731)

##### PDF
[https://arxiv.org/pdf/1903.03731](https://arxiv.org/pdf/1903.03731)

