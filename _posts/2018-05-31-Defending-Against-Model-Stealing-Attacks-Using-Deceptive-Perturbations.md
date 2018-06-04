---
layout: post
title: "Defending Against Model Stealing Attacks Using Deceptive Perturbations"
date: 2018-05-31 19:09:15
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Taesung Lee, Benjamin Edwards, Ian Molloy, Dong Su
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models are vulnerable to simple model stealing attacks if the adversary can obtain output labels for chosen inputs. To protect against these attacks, it has been proposed to limit the information provided to the adversary by omitting probability scores, significantly impacting the utility of the provided service. In this work, we illustrate how a service provider can still provide useful, albeit misleading, class probability information, while significantly limiting the success of the attack. Our defense forces the adversary to discard the class probabilities, requiring significantly more queries before they can train a model with comparable performance. We evaluate several attack strategies, model architectures, and hyperparameters under varying adversarial models, and evaluate the efficacy of our defense against the strongest adversary. Finally, we quantify the amount of noise injected into the class probabilities to mesure the loss in utility, e.g., adding 1.74 nats per query on CIFAR-10 and 3.27 on MNIST. Our extensive evaluation shows our defense can degrade the accuracy of the stolen model at least 20%, or require 4x more queries while keeping the accuracy of the protected model almost intact.

##### Abstract (translated by Google)
如果对手可以获得所选输入的输出标签，则机器学习模型容易受到简单模型窃取攻击的影响。为了防止这些攻击，已经提出通过省略概率分数来限制提供给对手的信息，这显着影响所提供的服务的效用。在这项工作中，我们举例说明了服务提供商仍然可以提供有用的，尽管具有误导性的班级概率信息，同时显着限制了攻击的成功。我们的防守迫使对手放弃阶级概率，在训练具有可比性能的模型之前需要更多的疑问。我们评估了各种攻击模式下的几种攻击策略，模型架构和超参数，并评估了我们对最强对手的防御效果。最后，我们量化注入类概率的噪声量以确定效用损失，例如，在CIFAR-10上增加1.74个nats，在MNIST上增加3.27个nats。我们的广泛评估表明，我们的防御能够降低被盗模型的准确性至少20％，或者需要4倍多的查询，同时保持受保护模型的准确性几乎完好无损。

##### URL
[http://arxiv.org/abs/1806.00054](http://arxiv.org/abs/1806.00054)

##### PDF
[http://arxiv.org/pdf/1806.00054](http://arxiv.org/pdf/1806.00054)

