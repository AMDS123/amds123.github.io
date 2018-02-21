---
layout: post
title: "Large Scale Novel Object Discovery in 3D"
date: 2018-02-20 11:39:15
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Quantitative
author: Siddharth Srivastava, Gaurav Sharma, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for discovering never-seen-before objects in 3D point clouds obtained from sensors like Microsoft Kinect. We generate supervoxels directly from the point cloud data and use them with a Siamese network, built on a recently proposed 3D convolutional neural network architecture. We use known objects to train a non-linear embedding of supervoxels, by optimizing the criteria that supervoxels which fall on the same object should be closer than those which fall on different objects, in the embedding space. We test on unknown objects, which were not seen during training, and perform clustering in the learned embedding space of supervoxels to effectively perform novel object discovery. We validate the method with extensive experiments, quantitatively showing that it can discover numerous unseen objects while being trained on only a few dense 3D models. We also show very good qualitative results of object discovery in point cloud data when the test objects, either specific instances or even categories, were never seen during training.

##### Abstract (translated by Google)
我们提供了一种用于发现从Microsoft Kinect等传感器获得的3D点云中前所未见的物体的方法。我们直接从点云数据生成超体素，并将它们与建立在最近提出的3D卷积神经网络体系结构上的Siamese网络一起使用。我们使用已知对象来训练超线性像素的非线性嵌入，通过优化落在同一对象上的超像素应该比落在不同对象上的超像素更接近嵌入空间的标准。我们测试未训练过的未知物体，并在超体素的学习嵌入空间中进行聚类，以有效地执行新物体发现。我们通过广泛的实验验证了该方法，定量表明它可以发现许多看不见的物体，同时仅在少数密集的3D模型上进行训练。在测试对象（特定实例甚至类别）在训练过程中从未见过测试对象时，我们还展示了点云数据中对象发现的非常好的定性结果。

##### URL
[http://arxiv.org/abs/1701.07046](http://arxiv.org/abs/1701.07046)

##### PDF
[http://arxiv.org/pdf/1701.07046](http://arxiv.org/pdf/1701.07046)

