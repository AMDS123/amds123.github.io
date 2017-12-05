---
layout: post
title: 'Where to put the Image in an Image Caption Generator'
date: 2017-12-06 02:46:07
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Marc Tanti (1), Albert Gatt (1), Kenneth P. Camilleri (1) ((1) University of Malta)
---

* content
{:toc}

##### Abstract
When a neural language model is used for caption generation, the image information can be fed to the neural network either by directly incorporating it in a recurrent neural network -- conditioning the language model by injecting image features -- or in a layer following the recurrent neural network -- conditioning the language model by merging the image features. While merging implies that visual features are bound at the end of the caption generation process, injecting can bind the visual features at a variety stages. In this paper we empirically show that late binding is superior to early binding in terms of different evaluation metrics. This suggests that the different modalities (visual and linguistic) for caption generation should not be jointly encoded by the RNN; rather, the multimodal integration should be delayed to a subsequent stage. Furthermore, this suggests that recurrent neural networks should not be viewed as actually generating text, but only as encoding it for prediction in a subsequent layer.

##### Abstract (translated by Google)
当使用神经语言模型进行字幕生成时，可以通过将图像信息直接并入到递归神经网络中来将图像信息馈送到神经网络 - 通过注入图像特征来调节语言模型 - 或者在重复神经网络 - 通过合并图像特征来调节语言模型。合并意味着视觉特征在标题生成过程结束时被绑定，注入可以在各个阶段绑定视觉特征。在本文中，我们凭经验证明，在不同的评估指标方面，迟绑定优于早绑定。这表明标题生成的不同形式（视觉和语言）不应该由RNN联合编码;相反，多式联运应该推迟到下一个阶段。此外，这表明经常性神经网络不应该被视为实际生成文本，而只是为了在随后的层中进行预测编码。

##### URL
[https://arxiv.org/abs/1703.09137](https://arxiv.org/abs/1703.09137)

