---
layout: post
title: 'What is the Role of Recurrent Neural Networks in an Image Caption Generator?'
date: 2017-08-25 15:40:00
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Marc Tanti, Albert Gatt, Kenneth P. Camilleri
---

* content
{:toc}

##### Abstract
In neural image captioning systems, a recurrent neural network (RNN) is typically viewed as the primary `generation' component. This view suggests that the image features should be `injected' into the RNN. This is in fact the dominant view in the literature. Alternatively, the RNN can instead be viewed as only encoding the previously generated words. This view suggests that the RNN should only be used to encode linguistic features and that only the final representation should be `merged' with the image features at a later stage. This paper compares these two architectures. We find that, in general, late merging outperforms injection, suggesting that RNNs are better viewed as encoders, rather than generators.

##### Abstract (translated by Google)
在神经图像字幕系统中，递归神经网络（RNN）通常被视为主要的“世代”组件。这个观点表明图像特征应该被注入到RNN中。这实际上是文学中的主导观点。或者，可以将RNN视为仅对先前生成的词进行编码。这个观点表明，RNN只能用来对语言特征进行编码，只有最后的表示应该在后期与图像特征“融合”。本文比较了这两种体系结构。我们发现，一般来说，后期合并优于注入，这表明RNN更好地被视为编码器，而不是发生器。

##### URL
[https://arxiv.org/abs/1708.02043](https://arxiv.org/abs/1708.02043)

