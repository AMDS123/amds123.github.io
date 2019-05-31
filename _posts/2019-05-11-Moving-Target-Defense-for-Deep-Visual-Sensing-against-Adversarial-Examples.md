---
layout: post
title: "Moving Target Defense for Deep Visual Sensing against Adversarial Examples"
date: 2019-05-11 08:22:32
categories: arXiv_AI
tags: arXiv_AI Adversarial Inference Classification Deep_Learning
author: Qun Song, Zhenyu Yan, Rui Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based visual sensing has achieved attractive accuracy but is shown vulnerable to adversarial example attacks. Specifically, once the attackers obtain the deep model, they can construct adversarial examples to mislead the model to yield wrong classification results. Deployable adversarial examples such as small stickers pasted on the road signs and lanes have been shown effective in misleading advanced driver-assistance systems. Many existing countermeasures against adversarial examples build their security on the attackers' ignorance of the defense mechanisms. Thus, they fall short of following Kerckhoffs's principle and can be subverted once the attackers know the details of the defense. This paper applies the strategy of moving target defense (MTD) to generate multiple new deep models after system deployment, that will collaboratively detect and thwart adversarial examples. Our MTD design is based on the adversarial examples' minor transferability to models differing from the one (e.g., the factory-designed model) used for attack construction. The post-deployment quasi-secret deep models significantly increase the bar for the attackers to construct effective adversarial examples. We also apply the technique of serial data fusion with early stopping to reduce the inference time by a factor of up to 5 while maintaining the sensing and defense performance. Extensive evaluation based on three datasets including a road sign image database and a GPU-equipped Jetson embedded computing board shows the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13148](http://arxiv.org/abs/1905.13148)

##### PDF
[http://arxiv.org/pdf/1905.13148](http://arxiv.org/pdf/1905.13148)

