---
layout: post
title: "360-Degree Textures of People in Clothing from a Single Image"
date: 2019-08-20 00:42:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Verica Lazova, Eldar Insafutdinov, Gerard Pons-Moll
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we predict a full 3D avatar of a person from a single image. We infer texture and geometry in the UV-space of the SMPL model using an image-to-image translation method. Given partial texture and segmentation layout maps derived from the input view, our model predicts the complete segmentation map, the complete texture map, and a displacement map. The predicted maps can be applied to the SMPL model in order to naturally generalize to novel poses, shapes, and even new clothing. In order to learn our model in a common UV-space, we non-rigidly register the SMPL model to thousands of 3D scans, effectively encoding textures and geometries as images in correspondence. This turns a difficult 3D inference task into a simpler image-to-image translation one. Results on rendered scans of people and images from the DeepFashion dataset demonstrate that our method can reconstruct plausible 3D avatars from a single image. We further use our model to digitally change pose, shape, swap garments between people and edit clothing. To encourage research in this direction we will make the source code available for research purpose.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07117](http://arxiv.org/abs/1908.07117)

##### PDF
[http://arxiv.org/pdf/1908.07117](http://arxiv.org/pdf/1908.07117)

