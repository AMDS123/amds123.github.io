---
layout: post
title: "Image Recognition Using Scale Recurrent Neural Networks"
date: 2018-03-25 09:16:55
categories: arXiv_CV
tags: arXiv_CV CNN RNN Recognition
author: Dong-Qing Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network(CNN) has been widely used for image recognition with great success. However, there are a number of limitations of the current CNN based image recognition paradigm. First, the receptive field of CNN is generally fixed, which limits its recognition capacity when the input image is very large. Second, it lacks the computational scalability for dealing with images with different sizes. Third, it is quite different from human visual system for image recognition, which involves both feadforward and recurrent proprocessing. This paper proposes a different paradigm of image recognition, which can take advantages of variable scales of the input images, has more computational scalabilities, and is more similar to image recognition by human visual system. It is based on recurrent neural network (RNN) defined on image scale with an embeded base CNN, which is named Scale Recurrent Neural Network(SRNN). This RNN based approach makes it easier to deal with images with variable sizes, and allows us to borrow existing RNN techniques, such as LSTM and GRU, to further enhance the recognition accuracy. Our experiments show that the recognition accuracy of a base CNN can be significantly boosted using the proposed SRNN models. It also significantly outperforms the scale ensemble method, which integrate the results of performing CNN to the input image at different scales, although the computational overhead of using SRNN is negligible.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经被广泛用于图像识别，取得了巨大的成功。然而，目前基于CNN的图像识别范例存在许多限制。首先，CNN的接受领域一般是固定的，这限制了其在输入图像非常大时的识别能力。其次，它缺乏处理不同大小图像的计算可伸缩性。第三，它与图像识别的人类视觉系统完全不同，它涉及前向和后向处理。本文提出了一种不同的图像识别范式，它可以利用输入图像的变尺度，具有更多的计算可扩展性，并且更接近于人类视觉系统的图像识别。它基于在图像尺度上定义的递归神经网络（RNN），嵌入基CNN被称为尺度递归神经网络（SRNN）。这种基于RNN的方法可以更容易地处理不同大小的图像，并且允许我们借用现有的RNN技术，例如LSTM和GRU，以进一步提高识别准确性。我们的实验表明，使用所提出的SRNN模型可以显着提高基本CNN的识别精度。它也明显优于规模集成方法，它将不同规模的CNN执行结果与输入图像集成在一起，尽管使用SRNN的计算开销可以忽略不计。

##### URL
[https://arxiv.org/abs/1803.09218](https://arxiv.org/abs/1803.09218)

##### PDF
[https://arxiv.org/pdf/1803.09218](https://arxiv.org/pdf/1803.09218)

