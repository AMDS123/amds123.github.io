---
layout: post
title: "Understanding and Controlling User Linkability in Decentralized Learning"
date: 2018-05-15 15:12:45
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Prediction Recognition
author: Tribhuvanesh Orekondy, Seong Joon Oh, Bernt Schiele, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning techniques are widely used by online services (e.g. Google, Apple) in order to analyze and make predictions on user data. As many of the provided services are user-centric (e.g. personal photo collections, speech recognition, personal assistance), user data generated on personal devices is key to provide the service. In order to protect the data and the privacy of the user, federated learning techniques have been proposed where the data never leaves the user's device and "only" model updates are communicated back to the server. In our work, we propose a new threat model that is not concerned with learning about the content - but rather is concerned with the linkability of users during such decentralized learning scenarios. 
 We show that model updates are characteristic for users and therefore lend themselves to linkability attacks. We show identification and matching of users across devices in closed and open world scenarios. In our experiments, we find our attacks to be highly effective, achieving 20x-175x chance-level performance. 
 In order to mitigate the risks of linkability attacks, we study various strategies. As adding random noise does not offer convincing operation points, we propose strategies based on using calibrated domain-specific data; we find these strategies offers substantial protection against linkability threats with little effect to utility.

##### Abstract (translated by Google)
机器学习技术被在线服务（例如Google，Apple）广泛使用，以便分析和预测用户数据。由于许多提供的服务是以用户为中心的（例如个人照片收集，语音识别，个人帮助），因此在个人设备上生成的用户数据是提供服务的关键。为了保护用户的数据和隐私，已经提出了联合学习技术，其中数据永远不会离开用户的设备，并且“仅”模型更新被传回服务器。在我们的工作中，我们提出了一种不关心内容学习的新威胁模型，而是关注用户在这种分散式学习场景中的可链接性。
 我们显示模型更新是用户的特征，因此适用于可链接性攻击。我们在封闭和开放的世界场景中展示用户跨设备的识别和匹配。在我们的实验中，我们发现我们的攻击非常有效，实现了20x-175x机会级别的性能。
 为了减轻可链接性攻击的风险，我们研究了各种策略。由于增加随机噪声不能提供令人信服的操作点，我们提出基于使用校准的特定领域数据的策略;我们发现这些策略提供了实质性的保护，防止对效用影响很小的可链接性威胁

##### URL
[http://arxiv.org/abs/1805.05838](http://arxiv.org/abs/1805.05838)

##### PDF
[http://arxiv.org/pdf/1805.05838](http://arxiv.org/pdf/1805.05838)

