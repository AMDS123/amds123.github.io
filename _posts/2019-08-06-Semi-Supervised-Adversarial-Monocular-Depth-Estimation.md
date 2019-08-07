---
layout: post
title: "Semi-Supervised Adversarial Monocular Depth Estimation"
date: 2019-08-06 13:19:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction
author: Rongrong Ji, Ke Li, Yan Wang, Xiaoshuai Sun, Feng Guo, Xiaowei Guo, Yongjian Wu, Feiyue Huang, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of monocular depth estimation when only a limited number of training image-depth pairs are available. To achieve a high regression accuracy, the state-of-the-art estimation methods rely on CNNs trained with a large number of image-depth pairs, which are prohibitively costly or even infeasible to acquire. Aiming to break the curse of such expensive data collections, we propose a semi-supervised adversarial learning framework that only utilizes a small number of image-depth pairs in conjunction with a large number of easily-available monocular images to achieve high performance. In particular, we use one generator to regress the depth and two discriminators to evaluate the predicted depth , i.e., one inspects the image-depth pair while the other inspects the depth channel alone. These two discriminators provide their feedbacks to the generator as the loss to generate more realistic and accurate depth predictions. Experiments show that the proposed approach can (1) improve most state-of-the-art models on the NYUD v2 dataset by effectively leveraging additional unlabeled data sources; (2) reach state-of-the-art accuracy when the training set is small, e.g., on the Make3D dataset; (3) adapt well to an unseen new dataset (Make3D in our case) after training on an annotated dataset (KITTI in our case).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02126](http://arxiv.org/abs/1908.02126)

##### PDF
[http://arxiv.org/pdf/1908.02126](http://arxiv.org/pdf/1908.02126)

