---
layout: post
title: 'Dual-Path Convolutional Image-Text Embedding'
date: 2017-11-22 02:40:11
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Zhedong Zheng, Liang Zheng, Michael Garrett, Yi Yang, Yi-Dong Shen
---

* content
{:toc}

##### Abstract
This paper considers the task of matching images and sentences. The challenge consists in discriminatively embedding the two modalities onto a shared visual-textual space. Existing work in this field largely uses Recurrent Neural Networks (RNN) for text feature learning and employs off-the-shelf Convolutional Neural Networks (CNN) for image feature extraction. Our system, in comparison, differs in two key aspects. Firstly, we build a convolutional network amenable for fine-tuning the visual and textual representations, where the entire network only contains four components, i.e., convolution layer, pooling layer, rectified linear unit function (ReLU), and batch normalisation. End-to-end learning allows the system to directly learn from the data and fully utilise the supervisions. Secondly, we propose instance loss according to viewing each multimodal data pair as a class. This works with a large margin objective to learn the inter-modal correspondence between images and their textual descriptions. Experiments on two generic retrieval datasets (Flickr30k and MSCOCO) demonstrate that our method yields competitive accuracy compared to state-of-the-art methods. Moreover, in language person retrieval, we improve the state of the art by a large margin. Code is available at https://github. com/layumi/Image-Text-Embedding

##### Abstract (translated by Google)
本文考虑匹配图像和句子的任务。挑战在于将两种模式有区别地嵌入共享的视觉文本空间。该领域的现有工作主要使用递归神经网络（RNN）进行文本特征学习，并使用现成的卷积神经网络（CNN）进行图像特征提取。相比之下，我们的系统在两个关键方面有所不同。首先，我们构建了一个卷积网络，用于微调视觉和文本表示，整个网络只包含四个部分，即卷积层，合并层，整形线性单元函数（ReLU）和批量归一化。端到端的学习使系统能够直接从数据中学习，充分利用监督。其次，根据将每个多模数据对视为一个类来提出实例丢失。这大大有助于学习图像与文本描述之间的模式对应。对两个通用检索数据集（Flickr30k和MSCOCO）的实验表明，与最先进的方法相比，我们的方法具有竞争性的准确性。而且，在语言人物检索方面，我们大大提高了艺术水平。代码可在https：// github上找到。 COM / layumi /图像文本嵌入

##### URL
[http://arxiv.org/abs/1711.05535](http://arxiv.org/abs/1711.05535)

