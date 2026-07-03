---
title: "CANListener: A Lightweight and Adaptive Intrusion Detection System for In-vehicle CAN Bus"
collection: publications
catogories: 
    - conference
permalink: /publication/2026-06-conference-CANListener-iwqos
#excerpt: ''
date: 2026-05-19
venue: 'Proceedings of IEEE/ACM IWQoS'
#paperurl: 'http://lynnlilu.github.io/files/.pdf'
citation: 'Jiacheng Jin, Yihe Zhang, Chong Zhang, Feng Lin, Xiaohang Wang, <b>Li Lu</b>*. &quot;CANListener: A Lightweight and Adaptive Intrusion Detection System for In-vehicle CAN Bus.&quot; <i>Proceedings of IEEE/ACM IWQoS</i>. Istanbul, Turkey. 2026. doi: to appear.'
---

This work received the Best Paper Runner-up Award of IEEE/ACM IWQoS 2026.

IEEE/ACM International Symposium on Quality of Service is a highly reputable forum to present novel ideas on all QoS-related subjects, which was established since 1993. IEEE/ACM IWQoS is a CCF-B conference.

Abstract: Controller Area Network (CAN) bus is the core communication backbone in modern vehicles, responsible for connecting Electronic Control Units (ECUs) and coordinating real-time in-vehicle operations. However, it is intrinsically without built-in security mechanisms. Existing works proposed Intrusion Detection Systems (IDS) to protect CAN bus, ranging from rule-based to machine learning and deep learning-based methods. But most of them either require significant labeled samples or computational resources, or they suffer from severe detection performance degradation. Toward this end, this paper proposes CANListener, a lightweight and adaptive IDS for in-vehicle CAN bus. CANListener first employs a Reinforced Active Learning (RAL)-based method to train detection models with minimal but valuable labeled samples, enabling label-effective but accurate learning. Then, it integrates a Reinforcement Learning (RL)-gated two-stage framework to dynamically allocate computational resources by routing inputs between lightweight and deep expert ensembles. Experimental results on real automotive datasets demonstrate that CANListener can achieve strong detection performance (99.48% TPR, 0.01% FPR) using only 1% labeled data, while maintaining real-time detection with an average CPU usage of 4.5% under hardware deployment

[To appear](https://lynnlilu.github.io/files/xxxx.pdf)
