---
layout: post
title: "Conditional Image Generation with PixelCNN Decoders"
date: 2016-06-18 15:44:24
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN RNN
author: Aaron van den Oord, Nal Kalchbrenner, Oriol Vinyals, Lasse Espeholt, Alex Graves, Koray Kavukcuoglu
mathjax: true
---

* content
{:toc}

##### Abstract
This work explores conditional image generation with a new image density model based on the PixelCNN architecture. The model can be conditioned on any vector, including descriptive labels or tags, or latent embeddings created by other networks. When conditioned on class labels from the ImageNet database, the model is able to generate diverse, realistic scenes representing distinct animals, objects, landscapes and structures. When conditioned on an embedding produced by a convolutional network given a single image of an unseen face, it generates a variety of new portraits of the same person with different facial expressions, poses and lighting conditions. We also show that conditional PixelCNN can serve as a powerful decoder in an image autoencoder. Additionally, the gated convolutional layers in the proposed model improve the log-likelihood of PixelCNN to match the state-of-the-art performance of PixelRNN on ImageNet, with greatly reduced computational cost.

##### Abstract (translated by Google)
这项工作探讨了基于PixelCNN架构的新的图像密度模型的条件图像生成。该模型可以适应任何矢量，包括描述性标签或标签，或由其他网络创建的潜在嵌入。当以ImageNet数据库中的类标签为条件时，该模型能够生成代表不同动物，物体，景观和结构的逼真场景。当以由卷积网络产生的嵌入作为条件时，给出单看一张看不见的脸的图像，它产生具有不同面部表情，姿势和光照条件的同一人的各种新肖像。我们还表明，条件PixelCNN可以作为一个图像自动编码器功能强大的解码器。另外，所提出的模型中的门控卷积层提高了PixelCNN的对数似然性，以匹配ImageNet上PixelRNN的最新性能，并大大降低了计算成本。

##### URL
[https://arxiv.org/abs/1606.05328](https://arxiv.org/abs/1606.05328)

##### PDF
[https://arxiv.org/pdf/1606.05328](https://arxiv.org/pdf/1606.05328)

