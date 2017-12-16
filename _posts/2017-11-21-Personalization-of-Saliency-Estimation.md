---
layout: post
title: "Personalization of Saliency Estimation"
date: 2017-11-21 19:10:44
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Attention GAN Prediction
author: Bingqing Yu, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing saliency models use low-level features or task descriptions when generating attention predictions. However, the link between observer characteristics and gaze patterns is rarely investigated. We present a novel saliency prediction technique which takes viewers' identities and personal traits into consideration when modeling human attention. Instead of only computing image salience for average observers, we consider the interpersonal variation in the viewing behaviors of observers with different personal traits and backgrounds. We present an enriched derivative of the GAN network, which is able to generate personalized saliency predictions when fed with image stimuli and specific information about the observer. Our model contains a generator which generates grayscale saliency heat maps based on the image and an observer label. The generator is paired with an adversarial discriminator which learns to distinguish generated salience from ground truth salience. The discriminator also has the observer label as an input, which contributes to the personalization ability of our approach. We evaluate the performance of our personalized salience model by comparison with a benchmark model along with other un-personalized predictions, and illustrate improvements in prediction accuracy for all tested observer groups.

##### Abstract (translated by Google)
在生成关注预测时，大多数现有的显着性模型都使用低级特征或任务描述。然而，观察者特征和注视模式之间的联系很少被调查。我们提出了一种新颖的显着性预测技术，在建模人的注意力时考虑到观众的身份和个人特征。我们不是仅仅为普通观察者计算图像显着性，而是考虑具有不同个人特征和背景的观察者的观察行为中的人际变化。我们提出了一个丰富的GAN网络的衍生物，当用图像刺激和关于观察者的特定信息馈送时，能够产生个性化的显着性预测。我们的模型包含一个生成器，根据图像和观察者标签生成灰度显着热图。发生器与敌对鉴别器配对，学会辨别所产生的显着性与地面真值显着性。鉴别器还具有观察者标签作为输入，这有助于我们的方法的个性化能力。我们通过与基准模型以及其他非个性化预测进行比较来评估我们的个性化显着性模型的性能，并说明所有测试观察者组的预测精度的改进。

##### URL
[https://arxiv.org/abs/1711.08000](https://arxiv.org/abs/1711.08000)

##### PDF
[https://arxiv.org/pdf/1711.08000](https://arxiv.org/pdf/1711.08000)

