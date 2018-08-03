---
layout: post
title: "MLCapsule: Guarded Offline Deployment of Machine Learning as a Service"
date: 2018-08-01 22:45:48
categories: arXiv_AI
tags: arXiv_AI Inference
author: Lucjan Hanzlik, Yang Zhang, Kathrin Grosse, Ahmed Salem, Max Augustin, Michael Backes, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
With the widespread use of machine learning (ML) techniques, ML as a service has become increasingly popular. In this setting, an ML model resides on a server and users can query the model with their data via an API. However, if the user's input is sensitive, sending it to the server is not an option. Equally, the service provider does not want to share the model by sending it to the client for protecting its intellectual property and pay-per-query business model. In this paper, we propose MLCapsule, a guarded offline deployment of machine learning as a service. MLCapsule executes the machine learning model locally on the user's client and therefore the data never leaves the client. Meanwhile, MLCapsule offers the service provider the same level of control and security of its model as the commonly used server-side execution. In addition, MLCapsule is applicable to offline applications that require local execution. Beyond protecting against direct model access, we demonstrate that MLCapsule allows for implementing defenses against advanced attacks on machine learning models such as model stealing/reverse engineering and membership inference.

##### Abstract (translated by Google)
随着机器学习（ML）技术的广泛使用，ML作为一项服务变得越来越流行。在此设置中，ML模型驻留在服务器上，用户可以通过API查询模型及其数据。但是，如果用户的输入是敏感的，则无法将其发送到服务器。同样，服务提供商不希望通过将模型发送到客户端来共享模型，以保护其知识产权和按查询付费的业务模型。在本文中，我们提出了MLCapsule，一种有保障的机器学习即服务的离线部署。 MLCapsule在用户的客户端本地执行机器学习模型，因此数据永远不会离开客户端。同时，MLCapsule为服务提供商提供与常用服务器端执行相同级别的控制和模型安全性。此外，MLCapsule适用于需要本地执行的脱机应用程序。除了防止直接模型访问之外，我们还证明了MLCapsule可以实现针对机器学习模型的高级攻击的防御，例如模型窃取/逆向工程和成员资格推理。

##### URL
[http://arxiv.org/abs/1808.00590](http://arxiv.org/abs/1808.00590)

##### PDF
[http://arxiv.org/pdf/1808.00590](http://arxiv.org/pdf/1808.00590)

