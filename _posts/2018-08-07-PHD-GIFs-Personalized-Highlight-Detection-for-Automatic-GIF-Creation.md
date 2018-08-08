---
layout: post
title: "PHD-GIFs: Personalized Highlight Detection for Automatic GIF Creation"
date: 2018-08-07 09:10:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Ana Garc&#xed;a del Molino, Michael Gygli
mathjax: true
---

* content
{:toc}

##### Abstract
Highlight detection models are typically trained to identify cues that make visual content appealing or interesting for the general public, with the objective of reducing a video to such moments. However, the "interestingness" of a video segment or image is subjective. Thus, such highlight models provide results of limited relevance for the individual user. On the other hand, training one model per user is inefficient and requires large amounts of personal information which is typically not available. To overcome these limitations, we present a global ranking model which conditions on each particular user's interests. Rather than training one model per user, our model is personalized via its inputs, which allows it to effectively adapt its predictions, given only a few user-specific examples. To train this model, we create a large-scale dataset of users and the GIFs they created, giving us an accurate indication of their interests. Our experiments show that using the user history substantially improves the prediction accuracy. On our test set of 850 videos, our model improves the recall by 8% with respect to generic highlight detectors. Furthermore, our method proves more precise than the user-agnostic baselines even with just one person-specific example.

##### Abstract (translated by Google)
突出显示检测模型通常被训练以识别使得视觉内容对于公众具有吸引力或感兴趣的提示，目的是将视频减少到这样的时刻。然而，视频片段或图像的“兴趣”是主观的。因此，这种突出显示模型提供了对个体用户的有限相关性的结果。另一方面，为每个用户训练一个模型是低效的并且需要大量通常不可用的个人信息。为了克服这些限制，我们提出了一个全球排名模型，它根据每个特定用户的兴趣来决定。我们的模型不是为每个用户培训一个模型，而是通过其输入进行个性化，这使得它可以有效地调整其预测，仅给出一些用户特定的示例。为了训练这个模型，我们创建了一个大型用户数据集和他们创建的GIF，让我们准确地指出他们的兴趣。我们的实验表明，使用用户历史可以显着提高预测精度。在我们的850个视频测试集中，我们的模型相对于通用高光探测器将召回率提高了8％。此外，即使仅使用一个特定于人的示例，我们的方法也比用户不可知的基线更精确。

##### URL
[http://arxiv.org/abs/1804.06604](http://arxiv.org/abs/1804.06604)

##### PDF
[http://arxiv.org/pdf/1804.06604](http://arxiv.org/pdf/1804.06604)

