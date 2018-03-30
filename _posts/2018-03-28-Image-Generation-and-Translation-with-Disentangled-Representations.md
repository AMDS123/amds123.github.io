---
layout: post
title: "Image Generation and Translation with Disentangled Representations"
date: 2018-03-28 12:53:01
categories: arXiv_AI
tags: arXiv_AI Image_Caption Adversarial GAN
author: Tobias Hinz, Stefan Wermter
mathjax: true
---

* content
{:toc}

##### Abstract
Generative models have made significant progress in the tasks of modeling complex data distributions such as natural images. The introduction of Generative Adversarial Networks (GANs) and auto-encoders lead to the possibility of training on big data sets in an unsupervised manner. However, for many generative models it is not possible to specify what kind of image should be generated and it is not possible to translate existing images into new images of similar domains. Furthermore, models that can perform image-to-image translation often need distinct models for each domain, making it hard to scale these systems to multiple domain image-to-image translation. We introduce a model that can do both, controllable image generation and image-to-image translation between multiple domains. We split our image representation into two parts encoding unstructured and structured information respectively. The latter is designed in a disentangled manner, so that different parts encode different image characteristics. We train an encoder to encode images into these representations and use a small amount of labeled data to specify what kind of information should be encoded in the disentangled part. A generator is trained to generate images from these representations using the characteristics provided by the disentangled part of the representation. Through this we can control what kind of images the generator generates, translate images between different domains, and even learn unknown data-generating factors while only using one single model.

##### Abstract (translated by Google)
生成模型在建模复杂数据分布（如自然图像）的任务中取得了重大进展。生成敌对网络（GAN）和自动编码器的引入使得可以以无监督的方式对大数据集进行训练。但是，对于许多生成模型，不可能指定应该生成哪种图像，并且不可能将现有图像转换为类似域的新图像。此外，可以执行图像到图像转换的模型通常需要每个域的不同模型，这使得很难将这些系统扩展到多域图像到图像转换。我们引入了一个模型，可以在多个域之间执行可控的图像生成和图像到图像的转换。我们将图像表示分为两部分，分别编码非结构化和结构化信息。后者是以解开的方式设计的，以便不同的部分编码不同的图像特征。我们训练编码器将图像编码到这些表示中，并使用少量的标记数据来指定在解开的部分中应编码哪种信息。训练生成器使用由表示的解开部分提供的特性从这些表示生成图像。通过这个，我们可以控制生成器生成的图像类型，在不同域之间转换图像，甚至可以学习未知数据生成因素，而只使用一个模型。

##### URL
[https://arxiv.org/abs/1803.10567](https://arxiv.org/abs/1803.10567)

##### PDF
[https://arxiv.org/pdf/1803.10567](https://arxiv.org/pdf/1803.10567)

