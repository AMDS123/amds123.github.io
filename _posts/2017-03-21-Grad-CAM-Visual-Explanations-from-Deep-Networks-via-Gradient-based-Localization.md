---
layout: post
title: "Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization"
date: 2017-03-21 23:48:00
categories: arXiv_CV
tags: arXiv_CV Adversarial QA Attention Reinforcement_Learning Caption CNN Image_Classification Classification Prediction VQA
author: Ramprasaath R. Selvaraju, Michael Cogswell, Abhishek Das, Ramakrishna Vedantam, Devi Parikh, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a technique for producing "visual explanations" for decisions from a large class of CNN-based models, making them more transparent. Our approach - Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients of any target concept, flowing into the final convolutional layer to produce a coarse localization map highlighting the important regions in the image for predicting the concept. Unlike previous approaches, GradCAM is applicable to a wide variety of CNN model-families: (1) CNNs with fully-connected layers (e.g. VGG), (2) CNNs used for structured outputs (e.g. captioning), (3) CNNs used in tasks with multimodal inputs (e.g. VQA) or reinforcement learning, without any architectural changes or re-training. We combine GradCAM with fine-grained visualizations to create a high-resolution class-discriminative visualization and apply it to off-the-shelf image classification, captioning, and visual question answering (VQA) models, including ResNet-based architectures. In the context of image classification models, our visualizations (a) lend insights into their failure modes (showing that seemingly unreasonable predictions have reasonable explanations), (b) are robust to adversarial images, (c) outperform previous methods on weakly-supervised localization, (d) are more faithful to the underlying model and (e) help achieve generalization by identifying dataset bias. For captioning and VQA, our visualizations show that even non-attention based models can localize inputs. Finally, we conduct human studies to measure if GradCAM explanations help users establish trust in predictions from deep networks and show that GradCAM helps untrained users successfully discern a "stronger" deep network from a "weaker" one. Our code is available at this https URL A demo and a video of the demo can be found at this http URL and youtu.be/COjUB9Izk6E.

##### Abstract (translated by Google)
我们提出了一种技术，用于为来自大量基于CNN的模型的决策产生“视觉解释”，使其更加透明。我们的方法 - 梯度加权类激活映射（Grad-CAM），使用任何目标概念的梯度，流入最终卷积层以生成粗略定位图，突出显示图像中的重要区域以预测概念。与以前的方法不同，GradCAM适用于各种CNN模型系列：（1）具有完全连接层的CNN（例如VGG），（2）用于结构化输出的CNN（例如字幕），（3）用于的CNN具有多模式输入（例如VQA）或强化学习的任务，无需任何架构更改或重新培训。我们将GradCAM与细粒度可视化相结合，以创建高分辨率的类辨别可视化，并将其应用于现成的图像分类，字幕和视觉问答（VQA）模型，包括基于ResNet的架构。在图像分类模型的背景下，我们的可视化（a）提供了对其失败模式的见解（表明看似不合理的预测具有合理的解释），（b）对对抗性图像具有鲁棒性，（c）优于以前的弱监督定位方法，（d）更忠实于基础模型，（e）通过识别数据集偏差来帮助实现泛化。对于字幕和VQA，我们的可视化显示即使是非基于注意力的模型也可以本地化输入。最后，我们进行人体研究，以衡量GradCAM解释是否有助于用户建立对深度网络预测的信任，并表明GradCAM帮助未经训练的用户成功地从“弱”的网络中识别出“更强”的深层网络。我们的代码可通过此https URL获得演示和演示视频可在此http URL和youtu.be/COjUB9Izk6E中找到。

##### URL
[https://arxiv.org/abs/1610.02391](https://arxiv.org/abs/1610.02391)

##### PDF
[https://arxiv.org/pdf/1610.02391](https://arxiv.org/pdf/1610.02391)

