---
layout: post
title: "Gray-box Adversarial Training"
date: 2018-08-06 07:26:44
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Vivek B.S., Konda Reddy Mopuri, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial samples are perturbed inputs crafted to mislead the machine learning systems. A training mechanism, called adversarial training, which presents adversarial samples along with clean samples has been introduced to learn robust models. In order to scale adversarial training for large datasets, these perturbations can only be crafted using fast and simple methods (e.g., gradient ascent). However, it is shown that adversarial training converges to a degenerate minimum, where the model appears to be robust by generating weaker adversaries. As a result, the models are vulnerable to simple black-box attacks. In this paper we, (i) demonstrate the shortcomings of existing evaluation policy, (ii) introduce novel variants of white-box and black-box attacks, dubbed gray-box adversarial attacks" based on which we propose novel evaluation method to assess the robustness of the learned models, and (iii) propose a novel variant of adversarial training, named Graybox Adversarial Training" that uses intermediate versions of the models to seed the adversaries. Experimental evaluation demonstrates that the models trained using our method exhibit better robustness compared to both undefended and adversarially trained model

##### Abstract (translated by Google)
对抗样本是扰乱机器学习系统的扰动输入。已经引入了一种称为对抗性训练的训练机制，该训练机制呈现对抗性样本以及干净的样本，以学习强大的模型。为了扩展大型数据集的对抗性训练，这些扰动只能使用快速简单的方法（例如，梯度上升）来制作。然而，显示对抗性训练收敛于退化最小值，其中模型通过产生较弱的对手看起来是稳健的。因此，这些模型很容易受到简单的黑盒攻击。在本文中，我们（i）展示了现有评估政策的缺点，（ii）引入了白盒和黑盒攻击的新变种，称为灰盒对抗性攻击“我们基于此提出新的评估方法来评估学习模型的稳健性，以及（iii）提出一种新的对抗性训练变体，名为“灰盒子对抗训练”，它使用模型的中间版本为对手播种。实验评估表明，与不设防和对侧训练的模型相比，使用我们的方法训练的模型表现出更好的稳健性

##### URL
[https://arxiv.org/abs/1808.01753](https://arxiv.org/abs/1808.01753)

##### PDF
[https://arxiv.org/pdf/1808.01753](https://arxiv.org/pdf/1808.01753)

