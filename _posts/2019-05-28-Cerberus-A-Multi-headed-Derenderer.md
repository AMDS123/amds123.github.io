---
layout: post
title: "Cerberus: A Multi-headed Derenderer"
date: 2019-05-28 17:00:03
categories: arXiv_CV
tags: arXiv_CV Relation
author: Boyang Deng, Simon Kornblith, Geoffrey Hinton
mathjax: true
---

* content
{:toc}

##### Abstract
To generalize to novel visual scenes with new viewpoints and new object poses, a visual system needs representations of the shapes of the parts of an object that are invariant to changes in viewpoint or pose. 3D graphics representations disentangle visual factors such as viewpoints and lighting from object structure in a natural way. It is possible to learn to invert the process that converts 3D graphics representations into 2D images, provided the 3D graphics representations are available as labels. When only the unlabeled images are available, however, learning to derender is much harder. We consider a simple model which is just a set of free floating parts. Each part has its own relation to the camera and its own triangular mesh which can be deformed to model the shape of the part. At test time, a neural network looks at a single image and extracts the shapes of the parts and their relations to the camera. Each part can be viewed as one head of a multi-headed derenderer. During training, the extracted parts are used as input to a differentiable 3D renderer and the reconstruction error is backpropagated to train the neural net. We make the learning task easier by encouraging the deformations of the part meshes to be invariant to changes in viewpoint and invariant to the changes in the relative positions of the parts that occur when the pose of an articulated body changes. Cerberus, our multi-headed derenderer, outperforms previous methods for extracting 3D parts from single images without part annotations, and it does quite well at extracting natural parts of human figures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11940](https://arxiv.org/abs/1905.11940)

##### PDF
[https://arxiv.org/pdf/1905.11940](https://arxiv.org/pdf/1905.11940)

