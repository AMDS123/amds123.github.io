---
layout: post
title: "Defense Against Adversarial Images using Web-Scale Nearest-Neighbor Search"
date: 2019-03-05 00:53:56
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Abhimanyu Dubey, Laurens van der Maaten, Zeki Yalniz, Yixuan Li, Dhruv Mahajan
mathjax: true
---

* content
{:toc}

##### Abstract
A plethora of recent work has shown that convolutional networks are not robust to adversarial images: images that are created by perturbing a sample from the data distribution as to maximize the loss on the perturbed example. In this work, we hypothesize that adversarial perturbations move the image away from the image manifold in the sense that there exists no physical process that could have produced the adversarial image. This hypothesis suggests that a successful defense mechanism against adversarial images should aim to project the images back onto the image manifold. We study such defense mechanisms, which approximate the projection onto the unknown image manifold by a nearest-neighbor search against a web-scale image database containing tens of billions of images. Empirical evaluations of this defense strategy on ImageNet suggest that it is very effective in attack settings in which the adversary does not have access to the image database. We also propose two novel attack methods to break nearest-neighbor defenses, and demonstrate conditions under which nearest-neighbor defense fails. We perform a series of ablation experiments, which suggest that there is a trade-off between robustness and accuracy in our defenses, that a large image database (with hundreds of millions of images) is crucial to get good performance, and that careful construction the image database is important to be robust against attacks tailored to circumvent our defenses.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01612](https://arxiv.org/abs/1903.01612)

##### PDF
[https://arxiv.org/pdf/1903.01612](https://arxiv.org/pdf/1903.01612)

