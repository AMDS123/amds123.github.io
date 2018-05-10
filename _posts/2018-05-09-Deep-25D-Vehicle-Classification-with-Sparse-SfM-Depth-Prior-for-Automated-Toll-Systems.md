---
layout: post
title: "Deep 2.5D Vehicle Classification with Sparse SfM Depth Prior for Automated Toll Systems"
date: 2018-05-09 13:28:52
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Classification
author: Georg Waltner, Michael Maurer, Thomas Holzmann, Patrick Ruprecht, Michael Opitz, Horst Possegger, Friedrich Fraundorfer, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
Automated toll systems rely on proper classification of the passing vehicles. This is especially difficult when the images used for classification only cover parts of the vehicle. To obtain information about the whole vehicle. we reconstruct the vehicle as 3D object and exploit this additional information within a Convolutional Neural Network (CNN). However, when using deep networks for 3D object classification, large amounts of dense 3D models are required for good accuracy, which are often neither available nor feasible to process due to memory requirements. Therefore, in our method we reproject the 3D object onto the image plane using the reconstructed points, lines or both. We utilize this sparse depth prior within an auxiliary network branch that acts as a regularizer during training. We show that this auxiliary regularizer helps to improve accuracy compared to 2D classification on a real-world dataset. Furthermore due to the design of the network, at test time only the 2D camera images are required for classification which enables the usage in portable computer vision systems.

##### Abstract (translated by Google)
自动收费系统依靠对过往车辆的正确分类。当用于分类的图像仅覆盖车辆的一部分时，这是特别困难的。获取有关整车的信息。我们将车辆重建为3D对象，并在卷积神经网络（CNN）内利用这些附加信息。但是，当使用深度网络进行三维物体分类时，需要大量密集的三维模型以获得较高的精确度，这通常既不可用也不可行，这是由于内存要求。因此，在我们的方法中，我们使用重构的点，线或两者将3D对象重投影到图像平面上。我们在辅助网络分支之前利用这个稀疏深度，在训练期间充当正规化者。我们证明这个辅助调整器有助于提高与真实世界数据集上2D分类相比的准确性。此外，由于网络的设计，在测试时间仅需要2D照相机图像进行分类，这使得便携式计算机视觉系统中的使用成为可能。

##### URL
[http://arxiv.org/abs/1805.03511](http://arxiv.org/abs/1805.03511)

##### PDF
[http://arxiv.org/pdf/1805.03511](http://arxiv.org/pdf/1805.03511)

