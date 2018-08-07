---
layout: post
title: "Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space"
date: 2017-04-12 06:39:52
categories: arXiv_CV
tags: arXiv_CV Image_Caption Face Caption Classification
author: Anh Nguyen, Jeff Clune, Yoshua Bengio, Alexey Dosovitskiy, Jason Yosinski
mathjax: true
---

* content
{:toc}

##### Abstract
Generating high-resolution, photo-realistic images has been a long-standing goal in machine learning. Recently, Nguyen et al. (2016) showed one interesting way to synthesize novel images by performing gradient ascent in the latent space of a generator network to maximize the activations of one or multiple neurons in a separate classifier network. In this paper we extend this method by introducing an additional prior on the latent code, improving both sample quality and sample diversity, leading to a state-of-the-art generative model that produces high quality images at higher resolutions (227x227) than previous generative models, and does so for all 1000 ImageNet categories. In addition, we provide a unified probabilistic interpretation of related activation maximization methods and call the general class of models "Plug and Play Generative Networks". PPGNs are composed of 1) a generator network G that is capable of drawing a wide range of image types and 2) a replaceable "condition" network C that tells the generator what to draw. We demonstrate the generation of images conditioned on a class (when C is an ImageNet or MIT Places classification network) and also conditioned on a caption (when C is an image captioning network). Our method also improves the state of the art of Multifaceted Feature Visualization, which generates the set of synthetic inputs that activate a neuron in order to better understand how deep neural networks operate. Finally, we show that our model performs reasonably well at the task of image inpainting. While image models are used in this paper, the approach is modality-agnostic and can be applied to many types of data.

##### Abstract (translated by Google)
生成高分辨率，照片般逼真的图像一直是机器学习的长期目标。最近，Nguyen等人。 （2016）展示了一种通过在发生器网络的潜在空间中执行梯度上升来合成新颖图像的有趣方式，以最大化单独分类器网络中的一个或多个神经元的激活。在本文中，我们通过在潜在代码上引入额外的先验来扩展此方法，提高样本质量和样本多样性，从而产生最先进的生成模型，以比以前更高的分辨率（227x227）生成高质量图像生成模型，适用于所有1000个ImageNet类别。此外，我们提供相关激活最大化方法的统一概率解释，并称为“即插即用生成网络”模型的一般类。 PPGN由1）能够绘制各种图像类型的发生器网络G和2）可更换的“条件”网络C组成，该网络告诉发生器要绘制什么。我们演示了以类为基础的图像生成（当C是ImageNet或MIT Places分类网络时），并且还以标题为条件（当C是图像字幕网络时）。我们的方法还改进了多面特征可视化的技术水平，它生成一组激活神经元的合成输入，以便更好地理解神经网络的深度运作。最后，我们证明了我们的模型在图像修复的任务中表现得相当好。虽然本文使用的是图像模型，但该方法与模态无关，可应用于多种类型的数据。

##### URL
[https://arxiv.org/abs/1612.00005](https://arxiv.org/abs/1612.00005)

##### PDF
[https://arxiv.org/pdf/1612.00005](https://arxiv.org/pdf/1612.00005)

