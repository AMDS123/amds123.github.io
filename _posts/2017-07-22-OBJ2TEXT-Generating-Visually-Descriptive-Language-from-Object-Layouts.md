---
layout: post
title: "OBJ2TEXT: Generating Visually Descriptive Language from Object Layouts"
date: 2017-07-22 04:17:42
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption RNN Detection
author: Xuwang Yin, Vicente Ordonez
mathjax: true
---

* content
{:toc}

##### Abstract
Generating captions for images is a task that has recently received considerable attention. In this work we focus on caption generation for abstract scenes, or object layouts where the only information provided is a set of objects and their locations. We propose OBJ2TEXT, a sequence-to-sequence model that encodes a set of objects and their locations as an input sequence using an LSTM network, and decodes this representation using an LSTM language model. We show that our model, despite encoding object layouts as a sequence, can represent spatial relationships between objects, and generate descriptions that are globally coherent and semantically relevant. We test our approach in a task of object-layout captioning by using only object annotations as inputs. We additionally show that our model, combined with a state-of-the-art object detector, improves an image captioning model from 0.863 to 0.950 (CIDEr score) in the test benchmark of the standard MS-COCO Captioning task.

##### Abstract (translated by Google)
为图像生成字幕是最近受到相当大关注的一项任务。在这项工作中，我们主要关注抽象场景的字幕生成，或者对象布局，其中唯一提供的信息是一组对象及其位置。我们提出了OBJ2TEXT，一种序列到序列模型，它使用LSTM网络将一组对象及其位置编码为输入序列，并使用LSTM语言模型对这种表示进行解码。我们显示尽管将对象布局编码为序列，但我们的模型可以表示对象之间的空间关系，并生成全局一致且语义相关的描述。我们通过仅使用对象注释作为输入来测试我们的对象布局字幕任务的方法。我们另外显示，我们的模型，结合最先进的目标检测器，在标准MS-COCO字幕任务的测试基准中，将图像字幕模型从0.863提高到0.950（CIDEr得分）。

##### URL
[https://arxiv.org/abs/1707.07102](https://arxiv.org/abs/1707.07102)

