---
layout: post
title: "Learning Single Camera Depth Estimation using Dual-Pixels"
date: 2019-04-11 16:25:43
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Rahul Garg, Neal Wadhwa, Sameer Ansari, Jonathan T. Barron
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques have enabled rapid progress in monocular depth estimation, but their quality is limited by the ill-posed nature of the problem and the scarcity of high quality datasets. We estimate depth from a single camera by leveraging the dual-pixel auto-focus hardware that is increasingly common on modern camera sensors. Classic stereo algorithms and prior learning-based depth estimation techniques under-perform when applied on this dual-pixel data, the former due to too-strong assumptions about RGB image matching, and the latter due to a lack of understanding of the optics of dual-pixel image formation. To allow learning based methods to work well on dual-pixel imagery, we identify an inherent ambiguity in the depth estimated from dual-pixel cues, and develop an approach to estimate depth up to this ambiguity. Using our approach, existing monocular depth estimation techniques can be effectively applied to dual-pixel data, and much smaller models can be constructed that still infer high quality depth. To demonstrate this, we capture a large dataset of in-the-wild 5-viewpoint RGB images paired with corresponding dual-pixel data, and show how view supervision with this data can be used to learn depth up to the unknown ambiguities. On our new task, our model is 30% more accurate than any prior work on learning-based monocular or stereoscopic depth estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05822](http://arxiv.org/abs/1904.05822)

##### PDF
[http://arxiv.org/pdf/1904.05822](http://arxiv.org/pdf/1904.05822)

