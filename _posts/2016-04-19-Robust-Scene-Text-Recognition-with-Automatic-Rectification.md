---
layout: post
title: "Robust Scene Text Recognition with Automatic Rectification"
date: 2016-04-19 14:44:54
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Baoguang Shi, Xinggang Wang, Pengyuan Lyu, Cong Yao, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing text in natural images is a challenging task with many unsolved problems. Different from those in documents, words in natural images often possess irregular shapes, which are caused by perspective distortion, curved character placement, etc. We propose RARE (Robust text recognizer with Automatic REctification), a recognition model that is robust to irregular text. RARE is a specially-designed deep neural network, which consists of a Spatial Transformer Network (STN) and a Sequence Recognition Network (SRN). In testing, an image is firstly rectified via a predicted Thin-Plate-Spline (TPS) transformation, into a more "readable" image for the following SRN, which recognizes text through a sequence recognition approach. We show that the model is able to recognize several types of irregular text, including perspective text and curved text. RARE is end-to-end trainable, requiring only images and associated text labels, making it convenient to train and deploy the model in practical systems. State-of-the-art or highly-competitive performance achieved on several benchmarks well demonstrates the effectiveness of the proposed model.

##### Abstract (translated by Google)
识别自然图像中的文本是一个具有挑战性的任务，有许多未解决的问题。与文档中的不同，自然图像中的单词往往具有不规则的形状，这是由透视失真，曲面字符放置等引起的。我们提出了一种对不规则文本具有鲁棒性的识别模型RARE（Robust text recognition with automatic REctification）。 RARE是一个专门设计的深度神经网络，由空间变换网络（STN）和序列识别网络（SRN）组成。在测试中，首先通过预测的薄板样条（TPS）转换将图像整形为用于以下SRN的更“可读”的图像，其通过序列识别方法识别文本。我们表明，该模型能够识别几种类型的不规则文本，包括透视文本和曲线文本。 RARE是端到端可训练的，只需要图像和相关文本标签，便于在实际系统中训练和部署模型。在几个基准上达到的最先进的或高度竞争的表现很好地证明了所提出的模型的有效性。

##### URL
[https://arxiv.org/abs/1603.03915](https://arxiv.org/abs/1603.03915)

##### PDF
[https://arxiv.org/pdf/1603.03915](https://arxiv.org/pdf/1603.03915)

