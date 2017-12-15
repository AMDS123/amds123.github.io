---
layout: post
title: "Cascaded Continuous Regression for Real-time Incremental Face Tracking"
date: 2016-08-06 21:03:34
categories: arXiv_CV
tags: arXiv_CV Face Tracking Detection
author: Enrique Sánchez-Lozano, Brais Martinez, Georgios Tzimiropoulos, Michel Valstar
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel real-time algorithm for facial landmark tracking. Compared to detection, tracking has both additional challenges and opportunities. Arguably the most important aspect in this domain is updating a tracker's models as tracking progresses, also known as incremental (face) tracking. While this should result in more accurate localisation, how to do this online and in real time without causing a tracker to drift is still an important open research question. We address this question in the cascaded regression framework, the state-of-the-art approach for facial landmark localisation. Because incremental learning for cascaded regression is costly, we propose a much more efficient yet equally accurate alternative using continuous regression. More specifically, we first propose cascaded continuous regression (CCR) and show its accuracy is equivalent to the Supervised Descent Method. We then derive the incremental learning updates for CCR (iCCR) and show that it is an order of magnitude faster than standard incremental learning for cascaded regression, bringing the time required for the update from seconds down to a fraction of a second, thus enabling real-time tracking. Finally, we evaluate iCCR and show the importance of incremental learning in achieving state-of-the-art performance. Code for our iCCR is available from this http URL

##### Abstract (translated by Google)
本文介绍了一种面部标志跟踪的新型实时算法。与检测相比，追踪既有额外的挑战也有机遇。可以说，这个领域最重要的方面就是跟踪器的模型更新，也就是增量（面部）跟踪。虽然这应该导致更准确的本地化，但是如何在不造成跟踪器漂移的情况下在线实时地进行这一操作仍然是一个重要的开放性研究问题。我们在级联回归框架中解决了这个问题，即面部标志物本地化的最新方法。因为级联回归的增量学习是昂贵的，所以我们使用连续回归来提出更高效但同样准确的替代方案。更具体地说，我们首先提出级联连续回归（CCR），并表明其准确性等同于监督下降法。然后，我们得出CCR（iCCR）的增量学习更新，并显示它比级联回归的标准增量学习快一个数量级，从而将更新所需的时间从几秒钟减少到几分之一秒，从而使实际-时间跟踪。最后，我们评估iCCR，并展示增量学习在实现最新性能方面的重要性。我们的iCCR代码可以从这个http URL获得

##### URL
[https://arxiv.org/abs/1608.01137](https://arxiv.org/abs/1608.01137)

##### PDF
[https://arxiv.org/pdf/1608.01137](https://arxiv.org/pdf/1608.01137)

