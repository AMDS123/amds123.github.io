---
layout: post
title: "When Regression Meets Manifold Learning for Object Recognition and Pose Estimation"
date: 2018-05-16 16:11:00
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Recognition
author: Mai Bui, Sergey Zakharov, Shadi Albarqouni, Slobodan Ilic, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a method for object recognition and pose estimation from depth images using convolutional neural networks. Previous methods addressing this problem rely on manifold learning to learn low dimensional viewpoint descriptors and employ them in a nearest neighbor search on an estimated descriptor space. In comparison we create an efficient multi-task learning framework combining manifold descriptor learning and pose regression. By combining the strengths of manifold learning using triplet loss and pose regression, we could either estimate the pose directly reducing the complexity compared to NN search, or use learned descriptor for the NN descriptor matching. By in depth experimental evaluation of the novel loss function we observed that the view descriptors learned by the network are much more discriminative resulting in almost 30% increase regarding relative pose accuracy compared to related works. On the other hand, regarding directly regressed poses we obtained important improvement compared to simple pose regression. By leveraging the advantages of both manifold learning and regression tasks, we are able to improve the current state-of-the-art for object recognition and pose retrieval that we demonstrate through in depth experimental evaluation.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种利用卷积神经网络从深度图像进行物体识别和姿态估计的方法。解决这个问题的以前的方法依赖于流形学习来学习低维视点描述符，并将它们用于估计描述符空间上的最近邻居搜索。相比之下，我们创建了一个高效的多任务学习框架，结合了流形描述符学习和姿态回归。通过结合利用三重损失和姿态回归的流形学习的优势，我们可以估计姿态直接降低与NN搜索相比的复杂度，或者使用学习描述符进行NN描述符匹配。通过对新损失函数的深入实验评估，我们观察到网络学习的视图描述符的判别性更强，导致与相关作品相比，相对姿态精度增加了近30％。另一方面，关于直接回归姿势，我们获得了重要的改善与简单姿态回归相比。通过利用流形学习和回归任务的优势，我们能够改进目前最先进的物体识别和姿态检索技术，我们通过深入的实验评估证明了这一点。

##### URL
[http://arxiv.org/abs/1805.06400](http://arxiv.org/abs/1805.06400)

##### PDF
[http://arxiv.org/pdf/1805.06400](http://arxiv.org/pdf/1805.06400)

