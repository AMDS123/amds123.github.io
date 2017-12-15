---
layout: post
title: "Bayesian Time-of-Flight for Realtime Shape, Illumination and Albedo"
date: 2015-07-22 13:18:14
categories: arXiv_CV
tags: arXiv_CV Inference
author: Amit Adam, Christoph Dann, Omer Yair, Shai Mazor, Sebastian Nowozin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a computational model for shape, illumination and albedo inference in a pulsed time-of-flight (TOF) camera. In contrast to TOF cameras based on phase modulation, our camera enables general exposure profiles. This results in added flexibility and requires novel computational approaches. To address this challenge we propose a generative probabilistic model that accurately relates latent imaging conditions to observed camera responses. While principled, realtime inference in the model turns out to be infeasible, and we propose to employ efficient non-parametric regression trees to approximate the model outputs. As a result we are able to provide, for each pixel, at video frame rate, estimates and uncertainty for depth, effective albedo, and ambient light intensity. These results we present are state-of-the-art in depth imaging. The flexibility of our approach allows us to easily enrich our generative model. We demonstrate that by extending the original single-path model to a two-path model, capable of describing some multipath effects. The new model is seamlessly integrated in the system at no additional computational cost. Our work also addresses the important question of optimal exposure design in pulsed TOF systems. Finally, for benchmark purposes and to obtain realistic empirical priors of multipath and insights into this phenomena, we propose a physically accurate simulation of multipath phenomena.

##### Abstract (translated by Google)
我们提出了一个在脉冲飞行时间（TOF）相机中的形状，照度和反照率推断的计算模型。与基于相位调制的TOF相机相比，我们的相机可以实现一般的曝光轮廓。这导致了增加的灵活性，并需要新的计算方法。为了解决这个挑战，我们提出了一个生成的概率模型，将潜在的成像条件精确地与观察到的相机响应联系起来。原则上，模型中的实时推断结果是不可行的，我们建议使用有效的非参数回归树来近似模型输出。因此，我们能够为每个像素提供视频帧率，深度，有效反照率和环境光强度的估计和不确定性。我们展示的这些结果是最新的深度成像技术。我们的方法的灵活性使我们能够轻松地丰富我们的生成模型。我们证明，通过将原始单路径模型扩展到双路径模型，能够描述一些多路径效应。新模型无缝集成在系统中，无需额外的计算成本。我们的工作也解决了脉冲TOF系统中最佳曝光设计的重要问题。最后，为了基准的目的，并获得现实的经验先验的多路径和洞察这种现象，我们提出了一个物理精确的多径现象模拟。

##### URL
[https://arxiv.org/abs/1507.06173](https://arxiv.org/abs/1507.06173)

##### PDF
[https://arxiv.org/pdf/1507.06173](https://arxiv.org/pdf/1507.06173)

