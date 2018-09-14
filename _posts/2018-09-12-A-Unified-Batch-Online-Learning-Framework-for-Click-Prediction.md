---
layout: post
title: "A Unified Batch Online Learning Framework for Click Prediction"
date: 2018-09-12 21:01:55
categories: arXiv_AI
tags: arXiv_AI Regularization Prediction
author: Rishabh Iyer, Nimit Acharya, Tanuja Bompada, Denis Charles, Eren Manavoglu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a unified framework for Batch Online Learning (OL) for Click Prediction in Search Advertisement. Machine Learning models once deployed, show non-trivial accuracy and calibration degradation over time due to model staleness. It is therefore necessary to regularly update models, and do so automatically. This paper presents two paradigms of Batch Online Learning, one which incrementally updates the model parameters via an early stopping mechanism, and another which does so through a proximal regularization. We argue how both these schemes naturally trade-off between old and new data. We then theoretically and empirically show that these two seemingly different schemes are closely related. Through extensive experiments, we demonstrate the utility of of our OL framework; how the two OL schemes relate to each other and how they trade-off between the new and historical data. We then compare batch OL to full model retrains, and show how online learning is more robust to data issues. We also demonstrate the long term impact of Online Learning, the role of the initial Models in OL, the impact of delays in the update, and finally conclude with some implementation details and challenges in deploying a real world online learning system in production. While this paper mostly focuses on application of click prediction for search advertisement, we hope that the lessons learned here can be carried over to other problem domains.

##### Abstract (translated by Google)
我们为搜索广告中的点击预测提供了批量在线学习（OL）的统一框架。机器学习模型一旦部署，由于模型陈旧性，随着时间的推移显示出非平凡的准确性和校准降级。因此，有必要定期更新模型，并自动执行此操作。本文介绍了两种批量在线学习的范例，一种是通过早期停止机制逐步更新模型参数，另一种是通过近端正则化来实现。我们争论这两种方案如何自然地在新旧数据之间进行权衡。然后我们在理论上和经验上表明这两种看似不同的方案密切相关。通过大量实验，我们证明了我们的OL框架的实用性;两个OL方案如何相互关联以及它们如何在新数据和历史数据之间进行权衡。然后，我们将批次OL与完整模型重新训练进行比较，并展示在线学习如何对数据问题更加健壮。我们还展示了在线学习的长期影响，初始模型在OL中的作用，更新延迟的影响，最后总结了在生产中部署真实世界在线学习系统的一些实现细节和挑战。虽然本文主要关注点击预测在搜索广告中的应用，但我们希望这里学到的经验可以转移到其他问题领域。

##### URL
[http://arxiv.org/abs/1809.04673](http://arxiv.org/abs/1809.04673)

##### PDF
[http://arxiv.org/pdf/1809.04673](http://arxiv.org/pdf/1809.04673)

