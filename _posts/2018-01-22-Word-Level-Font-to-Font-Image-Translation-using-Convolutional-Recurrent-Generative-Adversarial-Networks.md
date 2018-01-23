---
layout: post
title: "Word Level Font-to-Font Image Translation using Convolutional Recurrent Generative Adversarial Networks"
date: 2018-01-22 15:58:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Classification
author: Ankan Kumar Bhunia, Ayan Kumar Bhunia, Prithaj Banerjee, Aishik Konwer, Abir Bhowmick, Partha Pratim Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Conversion of one font to another font is very useful in real life applications. In this paper, we propose a Convolutional Recurrent Generative model to solve the word level font transfer problem. Our network is able to convert the font style of any printed text images from its current font to the required font. The network is trained end-to-end for the complete word images. Thus it eliminates the necessary pre-processing steps, like character segmentations. We extend our model to conditional setting that helps to learn one-to-many mapping function. We employ a novel convolutional recurrent model architecture in the Generator that efficiently deals with the word images of arbitrary width. It also helps to maintain the consistency of the final images after concatenating the generated image patches of target font. Besides, the Generator and the Discriminator network, we employ a Classification network to classify the generated word images of converted font style to their subsequent font categories. Most of the earlier works related to image translation are performed on square images. Our proposed architecture is the first work which can handle images of varying widths. Word images generally have varying width depending on the number of characters present. Hence, we test our model on a synthetically generated font dataset. We compare our method with some of the state-of-the-art methods for image translation. The superior performance of our network on the same dataset proves the ability of our model to learn the font distributions.

##### Abstract (translated by Google)
将一种字体转换为另一种字体在现实生活中非常有用。在本文中，我们提出了一个卷积递归生成模型来解决字级字体传输问题。我们的网络能够将任何打印文本图像的字体样式从当前字体转换为所需的字体。网络是完整的单词图像端对端培训。因此它消除了必要的预处理步骤，如字符分割。我们将我们的模型扩展到有助于学习一对多映射函数的条件设置。我们在发生器中使用了一种新的卷积循环模型架构，可有效地处理任意宽度的字图像。在连接生成的目标字体的图像块之后，还有助于保持最终图像的一致性。此外，在发生器和鉴别器网络中，我们使用分类网络将生成的转换后的字体样式的字图像分类为随后的字体类别。与图像翻译相关的早期大部分作品都是在正方形图像上进行的。我们提出的架构是第一个可以处理不同宽度图像的工作。字图像通常具有不同的宽度，取决于存在的字符的数量。因此，我们在合成生成的字体数据集上测试我们的模型。我们将我们的方法与一些最先进的图像翻译方法进行比较。我们的网络在相同数据集上的优越性能证明了我们模型学习字体分布的能力。

##### URL
[https://arxiv.org/abs/1801.07156](https://arxiv.org/abs/1801.07156)

##### PDF
[https://arxiv.org/pdf/1801.07156](https://arxiv.org/pdf/1801.07156)

