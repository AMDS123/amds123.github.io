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
我们提出了一种技术，用于为来自大型CNN模型的决策生成“视觉解释”，使其更加透明。我们的方法 - 渐变加权类激活映射（Grad-CAM），使用任何目标概念的梯度，流入最终的卷积层以产生粗糙的本地化图，突出图像中用于预测概念的重要区域。与以前的方法不同，GradCAM适用于各种各样的CNN模型族：（1）具有完全连接层的CNN（例如VGG），（2）用于结构化输出的CNN（例如字幕），（3）具有多模式输入（例如VQA）或强化学习的任务，而不需要任何架构改变或重新训练。我们将GradCAM与细粒度的可视化结合起来，创建高分辨率的类别判别式可视化，并将其应用于现成的图像分类，字幕和视觉问题回答（VQA）模型（包括基于ResNet的体系结构）。在图像分类模型的背景下，我们的可视化（a）提供洞察到他们的失败模式（表明看似不合理的预测有合理的解释），（b）对对抗图像是强大的，（c）超越以前的方法弱监督本地化（d）更忠实于基本模型，（e）通过识别数据集偏差来帮助实现概括。对于字幕和VQA，我们的可视化表明，即使不注意的模型也可以本地化投入。最后，我们进行人类研究，以衡量GradCAM解释是否有助于用户建立对来自深度网络的预测的信任，并显示GradCAM帮助未经训练的用户成功地从“较弱”的网络中辨别出“更强”的深度网络。我们的代码可以在这个https URL上获得演示和演示视频可以在这个http URL和youtu.be/COjUB9Izk6E上找到。

##### URL
[https://arxiv.org/abs/1610.02391](https://arxiv.org/abs/1610.02391)

##### PDF
[https://arxiv.org/pdf/1610.02391](https://arxiv.org/pdf/1610.02391)

