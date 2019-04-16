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
We propose a technique for producing "visual explanations" for decisions from a large class of CNN-based models, making them more transparent. Our approach - Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients of any target concept, flowing into the final convolutional layer to produce a coarse localization map highlighting the important regions in the image for predicting the concept. Unlike previous approaches, GradCAM is applicable to a wide variety of CNN model-families: (1) CNNs with fully-connected layers (e.g. VGG), (2) CNNs used for structured outputs (e.g. captioning), (3) CNNs used in tasks with multimodal inputs (e.g. VQA) or reinforcement learning, without any architectural changes or re-training. We combine GradCAM with fine-grained visualizations to create a high-resolution class-discriminative visualization and apply it to off-the-shelf image classification, captioning, and visual question answering (VQA) models, including ResNet-based architectures. In the context of image classification models, our visualizations (a) lend insights into their failure modes (showing that seemingly unreasonable predictions have reasonable explanations), (b) are robust to adversarial images, (c) outperform previous methods on weakly-supervised localization, (d) are more faithful to the underlying model and (e) help achieve generalization by identifying dataset bias. For captioning and VQA, our visualizations show that even non-attention based models can localize inputs. Finally, we conduct human studies to measure if GradCAM explanations help users establish trust in predictions from deep networks and show that GradCAM helps untrained users successfully discern a "stronger" deep network from a "weaker" one. Our code is available at this https URL. A demo and a video of the demo can be found at this http URL and youtu.be/COjUB9Izk6E.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.02391](https://arxiv.org/abs/1610.02391)

##### PDF
[https://arxiv.org/pdf/1610.02391](https://arxiv.org/pdf/1610.02391)

