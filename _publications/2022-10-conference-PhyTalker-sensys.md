---
title: "Push the Limit of Adversarial Example Attack on Speaker Recognition in Physical Domain"
collection: publications
catogories: 
    - conference
permalink: /publication/2022-10-conference-PhyTalker-sensys
#excerpt: ''
date: 2022-11-08
venue: 'The 20th ACM Conference on Embedded Networked Sensor Systems (ACM SenSys 2022)'
#paperurl: 'http://lynnlilu.github.io/files/08486283-2.pdf'
citation: 'Qianniu Chen, Meng Chen, <b>Li Lu*</b>, Jiadi Yu, Yingying Chen, Zhibo Wang, Zhongjie Ba, Feng Lin, Kui Ren. &quot;Push the Limit of Adversarial Example Attack on Speaker Recognition in Physical Domain.&quot; <i>Proceedings of ACM Conference on Embedded Networked Sensor Systems (ACM SenSys)</i>. Boston, MA, USA. pp. 710-724. 2022. doi: 10.1145/3560905.3568518.'
---

ACM Conference on Embedded Networked Sensor Systems is the premier international conference in embedded sensing and networking systems. ACM SenSys is also one of the conferences in Mobile Computing of CSRankings and a CCF-B conference. I am the corresponding author of this paper.

Abstract: The integration of deep learning on Speaker Recognition (SR) advances its development and wide deployment, but also introduces the emerging threat of adversarial examples. However, only a few existing studies investigate its practical threat in physical domain, which either evaluate its feasibility only by directly replaying generated adversarial examples, or explore the partial channel interference for robustness improvement. In this paper, we propose a physical adversarial example attack, PhyTalker, which could generate and inject perturbations on voices in a live-streaming manner on attacking various SR models in different physical channels. Compared with the typical adversarial example for digital attacks, PhyTalker generates a subphoneme-level perturbation dictionary to decouple the perturbation optimization and injection. Moreover, we introduce the channel augmentation to compensate both device and environmental distortions, as well as model ensemble to improve the perturbation transferability. Finally, PhyTalker recognizes and localizes the latest recorded phoneme to determine the corresponding perturbations for real-time broadcasting. Extensive experiments are conducted with a large-scale corpus in real physical scenarios, and results show that PhyTalker achieves an overall Attack Success Rate (ASR) of 85.5% in attacking mainstream SR systems and Mel Cepstral Distortion (MCD) of 2.45dB in human audibility.

[View the full paper](https://doi.org/10.1145/3560905.3568518)

[View presentation slide](https://lynnlilu.github.io/files/phytalker_sensys.pdf)

