---
layout: post
title: "Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models"
date: 2017-12-12 11:36:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Wieland Brendel, Jonas Rauber, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning algorithms are vulnerable to almost imperceptible perturbations of their inputs. So far it was unclear how much risk adversarial perturbations carry for the safety of real-world machine learning applications because most methods used to generate such perturbations rely either on detailed model information (gradient-based attacks) or on confidence scores such as class probabilities (score-based attacks), neither of which are available in most real-world scenarios. In many such cases one currently needs to retreat to transfer-based attacks which rely on cumbersome substitute models, need access to the training data and can be defended against. Here we emphasise the importance of attacks which solely rely on the final model decision. Such decision-based attacks are (1) applicable to real-world black-box models such as autonomous cars, (2) need less knowledge and are easier to apply than transfer-based attacks and (3) are more robust to simple defences than gradient- or score-based attacks. Previous attacks in this category were limited to simple models or simple datasets. Here we introduce the Boundary Attack, a decision-based attack that starts from a large adversarial perturbation and then seeks to reduce the perturbation while staying adversarial. The attack is conceptually simple, requires close to no hyperparameter tuning, does not rely on substitute models and is competitive with the best gradient-based attacks in standard computer vision tasks like ImageNet. We apply the attack on two black-box algorithms from Clarifai.com. The Boundary Attack in particular and the class of decision-based attacks in general open new avenues to study the robustness of machine learning models and raise new questions regarding the safety of deployed machine learning systems. An implementation of the attack is available as part of Foolbox at this https URL .

##### Abstract (translated by Google)
许多机器学习算法容易受到几乎不可察觉的输入扰动的影响。到目前为止，还不清楚对于现实世界的机器学习应用的安全性带来多大的风险对抗性扰动，因为用于产生这种扰动的大多数方法依赖于详细的模型信息（基于梯度的攻击）或者置信度分数，例如类别概率基于分数的攻击），在大多数现实世界的情况下都不可用。在许多这样的情况下，目前需要撤退到依靠繁琐的替代模型的基于转移的攻击，需要访问训练数据，并可以被捍卫。这里我们强调单纯依靠最终模型决定的攻击的重要性。这种基于决策的攻击是（1）适用于真实世界的黑盒模型，如自主汽车，（2）需要较少的知识，比基于传输的攻击更容易应用，（3）对于简单的防御更强大基于梯度或基于分数的攻击。以前的攻击只限于简单的模型或简单的数据集。在这里，我们介绍边界攻击，这是一个基于决策的攻击，从大的对抗性扰动开始，然后试图减少扰动，同时保持敌对状态。这个攻击在概念上是简单的，需要接近于没有超参数的调整，不依赖于替代模型，并且与ImageNet等标准计算机视觉任务中最好的基于梯度的攻击相竞争。我们将这个攻击应用于Clarifai.com的两个黑盒算法。边界攻击特别是一类基于决策的攻击为研究机器学习模型的稳健性开辟了新的途径，并提出了有关部署机器学习系统的安全性的新问题。这个攻击的实现可以作为这个https URL的Foolbox的一部分。

##### URL
[https://arxiv.org/abs/1712.04248](https://arxiv.org/abs/1712.04248)

##### PDF
[https://arxiv.org/pdf/1712.04248](https://arxiv.org/pdf/1712.04248)

