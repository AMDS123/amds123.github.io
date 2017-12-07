---
layout: post
title: "Self-Guiding Multimodal LSTM - when we do not have a perfect training dataset for image captioning"
date: 2017-09-15 02:53:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Yang Xian, Yingli Tian
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a self-guiding multimodal LSTM (sg-LSTM) image captioning model is proposed to handle uncontrolled imbalanced real-world image-sentence dataset. We collect FlickrNYC dataset from Flickr as our testbed with 306,165 images and the original text descriptions uploaded by the users are utilized as the ground truth for training. Descriptions in FlickrNYC dataset vary dramatically ranging from short term-descriptions to long paragraph-descriptions and can describe any visual aspects, or even refer to objects that are not depicted. To deal with the imbalanced and noisy situation and to fully explore the dataset itself, we propose a novel guiding textual feature extracted utilizing a multimodal LSTM (m-LSTM) model. Training of m-LSTM is based on the portion of data in which the image content and the corresponding descriptions are strongly bonded. Afterwards, during the training of sg-LSTM on the rest training data, this guiding information serves as additional input to the network along with the image representations and the ground-truth descriptions. By integrating these input components into a multimodal block, we aim to form a training scheme with the textual information tightly coupled with the image content. The experimental results demonstrate that the proposed sg-LSTM model outperforms the traditional state-of-the-art multimodal RNN captioning framework in successfully describing the key components of the input images.

##### Abstract (translated by Google)
本文提出了一种自引导多模式LSTM（sg-LSTM）图像字幕模型，用于处理不受控制的不平衡现实图像句子数据集。我们从Flickr收集FlickrNYC数据集作为我们的测试平台，包含306,165个图像，用户上传的原始文本描述被用作培训的基础。 FlickrNYC数据集中的描述从短期描述到长段描述变化很大，可以描述任何视觉方面，甚至可以引用未描述的对象。为了处理不平衡和嘈杂的情况，并充分挖掘数据集本身，我们提出了一种利用多模态LSTM（m-LSTM）模型提取的新颖的指导性文本特征。 m-LSTM的训练是基于图像内容和相应的描述被牢固地绑定在一起的数据部分。之后，在对其余训练数据进行sg-LSTM训练期间，这个指导信息作为对网络的附加输入以及图像表示和地面实况描述。通过将这些输入组件集成到多模块中，我们的目标是形成一个与文本信息紧密结合的图像内容的训练方案。实验结果表明，所提出的sg-LSTM模型在成功描述输入图像的关键部分方面优于传统的最先进的多模态RNN字幕框架。

##### URL
[https://arxiv.org/abs/1709.05038](https://arxiv.org/abs/1709.05038)

##### PDF
[https://arxiv.org/pdf/1709.05038](https://arxiv.org/pdf/1709.05038)

