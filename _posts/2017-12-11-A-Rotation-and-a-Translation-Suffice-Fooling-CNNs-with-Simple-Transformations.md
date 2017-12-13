---
layout: post
title: "A Rotation and a Translation Suffice: Fooling CNNs with Simple Transformations"
date: 2017-12-11 12:00:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Logan Engstrom, Dimitris Tsipras, Ludwig Schmidt, Aleksander Madry
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that neural network-based vision classifiers exhibit a significant vulnerability to misclassifications caused by imperceptible but adversarial perturbations of their inputs. These perturbations, however, are purely pixel-wise and built out of loss function gradients of either the attacked model or its surrogate. As a result, they tend to be contrived and look pretty artificial. This might suggest that such vulnerability to slight input perturbations can only arise in a truly adversarial setting and thus is unlikely to be an issue in more "natural" contexts. 
 In this paper, we provide evidence that such belief might be incorrect. We demonstrate that significantly simpler, and more likely to occur naturally, transformations of the input - namely, rotations and translations alone, suffice to significantly degrade the classification performance of neural network-based vision models across a spectrum of datasets. This remains to be the case even when these models are trained using appropriate data augmentation. Finding such "fooling" transformations does not require having any special access to the model - just trying out a small number of random rotation and translation combinations already has a significant effect. These findings suggest that our current neural network-based vision models might not be as reliable as we tend to assume. 
 Finally, we consider a new class of perturbations that combines rotations and translations with the standard pixel-wise attacks. We observe that these two types of input transformations are, in a sense, orthogonal to each other. Their effect on the performance of the model seems to be additive, while robustness to one type does not seem to affect the robustness to the other type. This suggests that this combined class of transformations is a more complete notion of similarity in the context of adversarial robustness of vision models.

##### Abstract (translated by Google)
最近的工作表明，基于神经网络的视觉分类器显示出由输入的不可察觉的但敌对的扰动引起的错误分类的明显脆弱性。然而，这些扰动纯粹是像素化的，并且是由被攻击的模型或其替代者的损失函数梯度构建的。因此，他们往往是人为的，看起来很人造。这可能表明，这种轻微的输入扰动的脆弱性只能出现在真正的对抗环境中，因此在更“自然”的情况下不太可能成为问题。
 在本文中，我们提供的证据表明这样的信念可能是不正确的。我们证明，输入的转换（即旋转和翻译本身）显着简单并且更可能自然发生，足以显着降低基于神经网络的视觉模型在一系列数据集上的分类性能。即使这些模型是使用适当的数据增强进行训练的，情况仍然如此。寻找这种“愚蠢的”转变并不需要对模型有任何特殊的使用 - 只是尝试少量的随机旋转和翻译组合已经有了重大的影响。这些发现表明，我们目前的基于神经网络的视觉模型可能不如我们倾向于假设的那样可靠。
 最后，我们考虑一种新的扰动类型，它将旋转和平移与标准的像素级攻击相结合。我们观察到，这两种类型的输入变换在某种意义上是相互正交的。它们对模型性能的影响似乎是相加的，而对一种类型的鲁棒性似乎不会影响对另一类型的鲁棒性。这表明，这种组合的转换类是在视觉模型的对抗鲁棒性的背景下的更完整的相似性概念。

##### URL
[http://arxiv.org/abs/1712.02779](http://arxiv.org/abs/1712.02779)

##### PDF
[http://arxiv.org/pdf/1712.02779](http://arxiv.org/pdf/1712.02779)

