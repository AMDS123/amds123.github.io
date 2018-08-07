---
layout: post
title: "Where to put the Image in an Image Caption Generator"
date: 2018-03-14 08:56:53
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model
author: Marc Tanti (1), Albert Gatt (1), Kenneth P. Camilleri (1) ((1) University of Malta)
mathjax: true
---

* content
{:toc}

##### Abstract
When a recurrent neural network language model is used for caption generation, the image information can be fed to the neural network either by directly incorporating it in the RNN -- conditioning the language model by `injecting' image features -- or in a layer following the RNN -- conditioning the language model by `merging' image features. While both options are attested in the literature, there is as yet no systematic comparison between the two. In this paper we empirically show that it is not especially detrimental to performance whether one architecture is used or another. The merge architecture does have practical advantages, as conditioning by merging allows the RNN's hidden state vector to shrink in size by up to four times. Our results suggest that the visual and linguistic modalities for caption generation need not be jointly encoded by the RNN as that yields large, memory-intensive models with few tangible advantages in performance; rather, the multimodal integration should be delayed to a subsequent stage.

##### Abstract (translated by Google)
当使用递归神经网络语言模型进行字幕生成时，可以通过将图像信息直接合并到RNN中来将图像信息馈送到神经网络 - 通过“注入”图像特征来调节语言模型 - 或者在随后的层中RNN  - 通过“合并”图像特征来调节语言模型。虽然文献中都证明了这两种选择，但两者之间尚未进行系统的比较。在本文中，我们凭经验表明，无论是使用一种架构还是其他架构，它对性能都不是特别有害。合并架构确实具有实际优势，因为通过合并进行调节允许RNN的隐藏状态向量缩小最多四倍。我们的结果表明，生成字幕的视觉和语言模式不需要由RNN联合编码，因为它产生大型，内存密集型模型，在性能上几乎没有明显的优势;相反，多模式整合应推迟到后续阶段。

##### URL
[https://arxiv.org/abs/1703.09137](https://arxiv.org/abs/1703.09137)

##### PDF
[https://arxiv.org/pdf/1703.09137](https://arxiv.org/pdf/1703.09137)

