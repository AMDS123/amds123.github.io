---
layout: post
title: "GeneGAN: Learning Object Transfiguration and Attribute Subspace from Unpaired Data"
date: 2017-05-14 08:59:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Image_Generation
author: Shuchang Zhou, Taihong Xiao, Yi Yang, Dieqiao Feng, Qinyao He, Weiran He
mathjax: true
---

* content
{:toc}

##### Abstract
Object Transfiguration replaces an object in an image with another object from a second image. For example it can perform tasks like "putting exactly those eyeglasses from image A on the nose of the person in image B". Usage of exemplar images allows more precise specification of desired modifications and improves the diversity of conditional image generation. However, previous methods that rely on feature space operations, require paired data and/or appearance models for training or disentangling objects from background. In this work, we propose a model that can learn object transfiguration from two unpaired sets of images: one set containing images that "have" that kind of object, and the other set being the opposite, with the mild constraint that the objects be located approximately at the same place. For example, the training data can be one set of reference face images that have eyeglasses, and another set of images that have not, both of which spatially aligned by face landmarks. Despite the weak 0/1 labels, our model can learn an "eyeglasses" subspace that contain multiple representatives of different types of glasses. Consequently, we can perform fine-grained control of generated images, like swapping the glasses in two images by swapping the projected components in the "eyeglasses" subspace, to create novel images of people wearing eyeglasses. Overall, our deterministic generative model learns disentangled attribute subspaces from weakly labeled data by adversarial training. Experiments on CelebA and Multi-PIE datasets validate the effectiveness of the proposed model on real world data, in generating images with specified eyeglasses, smiling, hair styles, and lighting conditions etc. The code is available online.

##### Abstract (translated by Google)
对象变换将图像中的对象替换为另一个图像中的另一个对象。例如，它可以执行诸如“将图像A中的那些眼镜正好放在图像B中的人的鼻子上”的任务。使用示例图像可以更精确地指定所需的修改，并改善条件图像生成的多样性。然而，依赖于特征空间操作的以前的方法要求配对的数据和/或外观模型用于训练或从背景解开对象。在这项工作中，我们提出了一个模型，可以从两个不成对的图像集学习对象变形：一个包含图像的“拥有”这种对象，另一个是相反的，具有温和的约束，对象所在大约在同一个地方。例如，训练数据可以是一组具有眼镜的参考人脸图像，以及另一组没有的图像，这两个图像在空间上通过人脸标志对齐。尽管0/1标签较弱，但我们的模型可以学习一个包含多个不同眼镜代表的“眼镜”子空间。因此，我们可以对生成的图像进行细粒度的控制，例如通过交换“眼镜”子空间中的投影组件来交换两个图像中的眼镜，以创建佩戴眼镜的人的新颖图像。总体而言，我们的确定性生成模型通过对抗训练来从弱标记的数据中学习解开的属性子空间。 CelebA和Multi-PIE数据集上的实验验证了所提出的模型在现实世界数据，在指定眼镜，微笑，发型和照明条件下生成图像的有效性。该代码可在线获得。

##### URL
[https://arxiv.org/abs/1705.04932](https://arxiv.org/abs/1705.04932)

##### PDF
[https://arxiv.org/pdf/1705.04932](https://arxiv.org/pdf/1705.04932)

