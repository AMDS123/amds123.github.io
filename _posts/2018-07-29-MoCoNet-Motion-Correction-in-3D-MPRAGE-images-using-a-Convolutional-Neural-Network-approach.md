---
layout: post
title: "MoCoNet: Motion Correction in 3D MPRAGE images using a Convolutional Neural Network approach"
date: 2018-07-29 09:24:54
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Kamlesh Pawar, Zhaolin Chen, N. Jon Shah, Gary F. Egan
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: The suppression of motion artefacts from MR images is a challenging task. The purpose of this paper is to develop a standalone novel technique to suppress motion artefacts from MR images using a data-driven deep learning approach. Methods: A deep learning convolutional neural network (CNN) was developed to remove motion artefacts in brain MR images. A CNN was trained on simulated motion corrupted images to identify and suppress artefacts due to the motion. The network was an encoder-decoder CNN architecture where the encoder decomposed the motion corrupted images into a set of feature maps. The feature maps were then combined by the decoder network to generate a motion-corrected image. The network was tested on an unseen simulated dataset and an experimental, motion corrupted in vivo brain dataset. Results: The trained network was able to suppress the motion artefacts in the simulated motion corrupted images, and the mean percentage error in the motion corrected images was 2.69 % with a standard deviation of 0.95 %. The network was able to effectively suppress the motion artefacts from the experimental dataset, demonstrating the generalisation capability of the trained network. Conclusion: A novel and generic motion correction technique has been developed that can suppress motion artefacts from motion corrupted MR images. The proposed technique is a standalone post-processing method that does not interfere with data acquisition or reconstruction parameters, thus making it suitable for a multitude of MR sequences.

##### Abstract (translated by Google)
目的：抑制MR图像中的运动伪影是一项具有挑战性的任务。本文的目的是开发一种独立的新技术，使用数据驱动的深度学习方法来抑制MR图像中的运动伪影。方法：开发了深度学习卷积神经网络（CNN）来去除脑MR图像中的运动伪影。 CNN在模拟运动损坏的图像上进行训练，以识别和抑制由于运动引起的伪影。该网络是编码器 - 解码器CNN架构，其中编码器将运动损坏的图像分解成一组特征图。然后由解码器网络组合特征图以生成运动校正图像。该网络在一个看不见的模拟数据集和一个实验的运动损坏的体内大脑数据集上进行了测试。结果：训练好的网络能够抑制模拟运动损伤图像中的运动伪影，运动校正图像中的平均百分误差为2.69％，标准差为0.95％。网络能够有效地抑制来自实验数据集的运动伪影，展示了训练网络的泛化能力。结论：已经开发出一种新颖且通用的运动校正技术，该技术可以抑制运动损坏的MR图像中的运动伪影。所提出的技术是独立的后处理方法，其不干扰数据采集或重建参数，因此使其适用于多个MR序列。

##### URL
[http://arxiv.org/abs/1807.10831](http://arxiv.org/abs/1807.10831)

##### PDF
[http://arxiv.org/pdf/1807.10831](http://arxiv.org/pdf/1807.10831)

