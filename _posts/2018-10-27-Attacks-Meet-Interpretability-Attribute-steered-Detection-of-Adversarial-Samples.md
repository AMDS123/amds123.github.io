---
layout: post
title: "Attacks Meet Interpretability: Attribute-steered Detection of Adversarial Samples"
date: 2018-10-27 02:32:32
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Face Inference Classification Detection Recognition Face_Recognition
author: Guanhong Tao, Shiqing Ma, Yingqi Liu, Xiangyu Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial sample attacks perturb benign inputs to induce DNN misbehaviors. Recent research has demonstrated the widespread presence and the devastating consequences of such attacks. Existing defense techniques either assume prior knowledge of specific attacks or may not work well on complex models due to their underlying assumptions. We argue that adversarial sample attacks are deeply entangled with interpretability of DNN models: while classification results on benign inputs can be reasoned based on the human perceptible features/attributes, results on adversarial samples can hardly be explained. Therefore, we propose a novel adversarial sample detection technique for face recognition models, based on interpretability. It features a novel bi-directional correspondence inference between attributes and internal neurons to identify neurons critical for individual attributes. The activation values of critical neurons are enhanced to amplify the reasoning part of the computation and the values of other neurons are weakened to suppress the uninterpretable part. The classification results after such transformation are compared with those of the original model to detect adversaries. Results show that our technique can achieve 94% detection accuracy for 7 different kinds of attacks with 9.91% false positives on benign inputs. In contrast, a state-of-the-art feature squeezing technique can only achieve 55% accuracy with 23.3% false positives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11580](http://arxiv.org/abs/1810.11580)

##### PDF
[http://arxiv.org/pdf/1810.11580](http://arxiv.org/pdf/1810.11580)

