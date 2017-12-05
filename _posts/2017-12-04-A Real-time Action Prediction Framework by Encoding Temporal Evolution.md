---
layout: post
title:  'A Real-time Action Prediction Framework by Encoding Temporal Evolution'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Fahimeh Rezazadegan, Sareh Shirazi, Larry S. Davis
---

* content
{:toc}

##### Abstract
Anticipating future actions is a key component of intelligence, specifically when it applies to real-time systems, such as robots or autonomous cars. While recent work has addressed prediction of raw RGB pixel values in future video frames, we focus on predicting further in future by predicting a summary of moving pixels through a sequence of frames which we call dynamic images. More precisely, given a dynamic image, we predict the motion evolution through next unseen video frames. Since this representation consists of a sequence of frames, we can go one second further into the future compared to the previous work in this field. We employed convolutional LSTMs to train our network on the dynamic images in an unsupervised learning process. Since our final goal is predicting the next action of a complex task such as an assembly task, we exploited labelled actions for the recognition process on top of predicted dynamic images. We show the effectiveness of our method on predicting the next human action in the above-mentioned task through the two-step process of predicting the next dynamic image and recognizing the action which it represents.

##### Abstract (translated by Google)
预测未来的行动是情报的关键组成部分，特别是当它适用于实时系统，如机器人或自动驾驶汽车。虽然最近的工作已经解决了未来视频帧中原始RGB像素值的预测问题，但是通过预测动态像素的概要，我们将重点进一步预测未来的视频帧。更准确地说，给定一个动态图像，我们预测通过未来看不见的视频帧的运动发展。由于这种表示是由一系列帧组成的，所以与以前在这个领域的工作相比，我们可以进一步走向未来一秒。我们采用卷积LSTM在无监督学习过程中对动态图像进行网络训练。由于我们的最终目标是预测复杂任务（如装配任务）的下一步行动，因此我们在预测的动态图像之上利用了标记的识别过程。我们通过预测下一个动态图像和识别它所代表的动作的两个步骤来展示我们的方法在预测上述任务中的下一个人的行为方面的有效性。

