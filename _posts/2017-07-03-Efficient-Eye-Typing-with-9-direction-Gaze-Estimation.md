---
layout: post
title: "Efficient Eye Typing with 9-direction Gaze Estimation"
date: 2017-07-03 13:51:13
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Language_Model
author: Chi Zhang, Rui Yao, Jinpeng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Vision based text entry systems aim to help disabled people achieve text communication using eye movement. Most previous methods have employed an existing eye tracker to predict gaze direction and design an input method based upon that. However, these methods can result in eye tracking quality becoming easily affected by various factors and lengthy amounts of time for calibration. Our paper presents a novel efficient gaze based text input method, which has the advantage of low cost and robustness. Users can type in words by looking at an on-screen keyboard and blinking. Rather than estimate gaze angles directly to track eyes, we introduce a method that divides the human gaze into nine directions. This method can effectively improve the accuracy of making a selection by gaze and blinks. We build a Convolutional Neural Network (CNN) model for 9-direction gaze estimation. On the basis of the 9-direction gaze, we use a nine-key T9 input method which is widely used in candy bar phones. Bar phones were very popular in the world decades ago and have cultivated strong user habits and language models. To train a robust gaze estimator, we created a large-scale dataset with images of eyes sourced from 25 people. According to the results from our experiments, our CNN model is able to accurately estimate different people's gaze under various lighting conditions by different devices. In considering disable people's needs, we removed the complex calibration process. The input methods can run in screen mode and portable off-screen mode. Moreover, The datasets used in our experiments are made available to the community to allow further experimentation.

##### Abstract (translated by Google)
基于视觉的文本输入系统旨在帮助残疾人使用眼球运动实现文本交流。大多数以前的方法已经采用了现有的眼动仪来预测注视方向并基于此设计输入方法。然而，这些方法可能导致眼睛跟踪质量容易受到各种因素和长时间校准的影响。本文提出了一种基于高效注视的文本输入方法，具有成本低，鲁棒性好的优点。用户可以通过查看屏幕上的键盘并闪烁输入文字。我们不是直接估计注视角度来跟踪眼睛，而是引入一种方法，将人眼分成九个方向。该方法可以有效提高注视和眨眼选择的准确性。我们建立了9方向凝视估计的卷积神经网络（CNN）模型。在9方向凝视的基础上，我们采用了广泛用于直板手机的九键T9输入法。酒吧电话在数十年前就非常流行，培养了强大的用户习惯和语言模式。为了训练一个强大的凝视估计器，我们创建了一个大型的数据集，其中有来自25个人的眼睛图像。根据我们的实验结果，我们的CNN模型能够准确地估计不同的设备在不同的照明条件下的不同的人的凝视。考虑到禁用人们的需求，我们删除了复杂的校准过程。输入法可以在屏幕模式和可移动的离屏模式下运行。此外，在我们的实验中使用的数据集提供给社区进行进一步的实验。

##### URL
[https://arxiv.org/abs/1707.00548](https://arxiv.org/abs/1707.00548)

##### PDF
[https://arxiv.org/pdf/1707.00548](https://arxiv.org/pdf/1707.00548)

