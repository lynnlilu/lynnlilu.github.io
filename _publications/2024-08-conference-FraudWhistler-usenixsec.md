---
title: "FraudWhistler: A Resilient, Robust and Plug-and-play Adversarial Example Detection Method for Speaker Recognition"
collection: publications
catogories: 
    - conference
permalink: /publication/2024-08-conference-FraudWhistler-usenixsec
#excerpt: ''
date: 2024-08-14
venue: 'Proceedings of USENIX Security Symposium'
#paperurl: 'http://lynnlilu.github.io/files/.pdf'
citation: 'Kun Wang, Xiangyu Xu, <b>Li Lu</b>*, Zhongjie Ba, Feng Lin, Kui Ren. &quot;FraudWhistler: A Resilient, Robust and Plug-and-play Adversarial Example Detection Method for Speaker Recognition.&quot; <i>Proceedings of USENIX Security Symposium</i>. Philadelphia, PA, USA. 2024. doi: to appear.'
---

USENIX Security Symposium is one of the Top-Four international conferences on cyber security. USENIX SEC is a CCF-A conference.

Abstract: With the in-depth integration of deep learning, state-of-theart speaker recognition systems have achieved breakthrough progress. However, the intrinsic vulnerability of deep learning to Adversarial Example (AE) attacks has brought new severe threats to real-world speaker recognition systems. In this paper, we propose FraudWhistler, a practical AE detection system, which is resilient to various AE attacks, robust in complex physical environments, and plug-and-play for deployed systems. Its basic idea is to make use of an intrinsic characteristic of AE, ie, the instability of model prediction for AE, which is totally different from benign samples. FraudWhistler generates several audio variants for the original audio sample with some distortion techniques, obtains multiple outputs of the speaker recognition system for these audio variants, and based on that FraudWhistler extracts some statistics representing the instability of the original audio sample and further trains a one-class SVM classifier to detect adversarial example. 


[View the full paper](https://www.usenix.org/system/files/sec23winter-prepub-168-wang-kun.pdf)
