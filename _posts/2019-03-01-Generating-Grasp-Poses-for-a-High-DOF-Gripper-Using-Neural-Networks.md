---
layout: post
title: "Generating Grasp Poses for a High-DOF Gripper Using Neural Networks"
date: 2019-03-01 17:39:02
categories: arXiv_RO
tags: arXiv_RO
author: Min Liu, Zherong Pan, Kai Xu, Kanishka Ganguly, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning-based method to represent grasp poses of a high-DOF hand using neural networks. Due to the redundancy in such high-DOF grippers, there exists a large number of equally effective grasp poses for a given target object, making it difficult for the neural network to find consistent grasp poses. In other words, it is difficult to find grasp poses for many objects that can be represented by a single neural network. We resolve this ambiguity by generating an augmented dataset that covers many possible grasps for each target object and train our neural networks using a consistency loss function to identify a one-to-one mapping from objects to grasp poses. We further enhance the quality of neuralnetwork-predicted grasp poses using an additional collision loss function to avoid penetrations. We show that our method can generate high-DOF grasp poses with higher accuracy than supervised learning baselines. The quality of grasp poses are on par with the groundtruth poses in the dataset. In addition, our method is robust and can handle imperfect or inaccurate object models, such as those constructed from multi-view depth images, allowing our method to be implemented on a 25-DOF Shadow Hand hardware platform.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00425](http://arxiv.org/abs/1903.00425)

##### PDF
[http://arxiv.org/pdf/1903.00425](http://arxiv.org/pdf/1903.00425)

