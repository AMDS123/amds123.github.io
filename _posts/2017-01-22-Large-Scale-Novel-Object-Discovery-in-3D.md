---
layout: post
title: "Large Scale Novel Object Discovery in 3D"
date: 2017-01-22 12:58:52
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Quantitative
author: Siddharth Srivastava, Gaurav Sharma, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for discovering objects in 3D point clouds from sensors like Microsoft Kinect. We utilize supervoxels generated directly from the point cloud data and design a Siamese network building on a recently proposed 3D convolutional neural network architecture. At training, we assume the availability of the some known objects---these are used to train a non-linear embedding of supervoxels using the Siamese network, by optimizing the criteria that supervoxels which fall on the same object should be closer than those which fall on different objects, in the embedding space. We do not assume the objects during test to be known, and perform clustering, in the embedding space learned, of supervoxels to effectively perform novel object discovery. We validate the method with quantitative results showing that it can discover numerous unseen objects while being trained on only a few dense 3D models. We also show convincing qualitative results of object discovery in point cloud data when the test objects, either specific instances or even their categories, were never seen during training.

##### Abstract (translated by Google)
我们介绍一种从微软Kinect等传感器中发现三维点云中的物体的方法。我们利用直接从点云数据生成的超体素，并在最近提出的三维卷积神经网络体系结构上设计一个连体网络。在训练中，我们假定已知对象的可用性---这些被用来训练使用连体网络的超线性像素的非线性嵌入，通过优化落在相同对象上的超像素的标准比那些落在不同的物体上，在嵌入空间中。我们不假设测试过程中的对象是已知的，并且在所学习的嵌入空间中对超体素进行聚类，以有效地执行新的对象发现。我们通过定量的结果验证了该方法，该方法可以在仅仅几个密集的三维模型上进行训练的同时发现许多看不见的物体。当测试对象，特定的实例，甚至是它们的类别，在训练过程中都没有看到，我们也展示了在点云数据中对象发现的令人信服的定性结果。

##### URL
[https://arxiv.org/abs/1701.07046](https://arxiv.org/abs/1701.07046)

##### PDF
[https://arxiv.org/pdf/1701.07046](https://arxiv.org/pdf/1701.07046)

