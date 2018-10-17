---
layout: post
title: "Pose Estimation for Objects with Rotational Symmetry"
date: 2018-10-13 01:40:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Embedding
author: Enric Corona, Kaustav Kundu, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Pose estimation is a widely explored problem, enabling many robotic tasks such as grasping and manipulation. In this paper, we tackle the problem of pose estimation for objects that exhibit rotational symmetry, which are common in man-made and industrial environments. In particular, our aim is to infer poses for objects not seen at training time, but for which their 3D CAD models are available at test time. Previous work has tackled this problem by learning to compare captured views of real objects with the rendered views of their 3D CAD models, by embedding them in a joint latent space using neural networks. We show that sidestepping the issue of symmetry in this scenario during training leads to poor performance at test time. We propose a model that reasons about rotational symmetry during training by having access to only a small set of symmetry-labeled objects, whereby exploiting a large collection of unlabeled CAD models. We demonstrate that our approach significantly outperforms a naively trained neural network on a new pose dataset containing images of tools and hardware.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05780](https://arxiv.org/abs/1810.05780)

##### PDF
[https://arxiv.org/pdf/1810.05780](https://arxiv.org/pdf/1810.05780)

