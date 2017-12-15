---
layout: post
title: "Unsupervised neural and Bayesian models for zero-resource speech processing"
date: 2017-01-03 22:26:10
categories: arXiv_SD
tags: arXiv_SD Knowledge Segmentation Represenation_Learning Language_Model
author: Herman Kamper
mathjax: true
---

* content
{:toc}

##### Abstract
In settings where only unlabelled speech data is available, zero-resource speech technology needs to be developed without transcriptions, pronunciation dictionaries, or language modelling text. There are two central problems in zero-resource speech processing: (i) finding frame-level feature representations which make it easier to discriminate between linguistic units (phones or words), and (ii) segmenting and clustering unlabelled speech into meaningful units. In this thesis, we argue that a combination of top-down and bottom-up modelling is advantageous in tackling these two problems. To address the problem of frame-level representation learning, we present the correspondence autoencoder (cAE), a neural network trained with weak top-down supervision from an unsupervised term discovery system. By combining this top-down supervision with unsupervised bottom-up initialization, the cAE yields much more discriminative features than previous approaches. We then present our unsupervised segmental Bayesian model that segments and clusters unlabelled speech into hypothesized words. By imposing a consistent top-down segmentation while also using bottom-up knowledge from detected syllable boundaries, our system outperforms several others on multi-speaker conversational English and Xitsonga speech data. Finally, we show that the clusters discovered by the segmental Bayesian model can be made less speaker- and gender-specific by using features from the cAE instead of traditional acoustic features. In summary, the different models and systems presented in this thesis show that both top-down and bottom-up modelling can improve representation learning, segmentation and clustering of unlabelled speech data.

##### Abstract (translated by Google)
在只有未标记的语音数据可用的设置中，零资源语音技术需要在没有转录，发音词典或语言建模文本的情况下开发。有在零资源语音处理两个中心问题：（ⅰ）找到帧级特征表示，这使得它更易于语言单位（电话或字）之间进行区分，和（ii）分段和聚类的未标记的语音转换成有意义的单位。在本文中，我们认为自上而下和自下而上的建模相结合，有利于解决这两个问题。为了解决帧级表示学习的问题，我们提出了函数自动编码器（cAE），这是一个用无监督的词条发现系统训练的弱天然神经网络。通过将这种自顶向下的监督与无监督的自下而上的初始化相结合，cAE比以前的方法产生更多的判别特征。然后，我们提出我们的无监督分段贝叶斯模型，将未标记的语音分割和聚类成虚拟词语。通过强调一致的自顶向下分割，同时也使用自下而上的检测音节边界的知识，我们的系统胜过其他几个多人说话会话英语和Xitsonga语音数据。最后，我们表明，通过使用来自cAE的特征而不是传统的声学特征，通过分段贝叶斯模型发现的聚类可以减少讲话者和性别特定。综上所述，本文提出的不同模型和系统表明，自上而下和自下而上的建模可以改善未标注语音数据的表示学习，分割和聚类。

##### URL
[https://arxiv.org/abs/1701.00851](https://arxiv.org/abs/1701.00851)

##### PDF
[https://arxiv.org/pdf/1701.00851](https://arxiv.org/pdf/1701.00851)

