---
title: "Hijacking Large Audio-Language Models via Context-Agnostic and Imperceptible Auditory Prompt Injection"
collection: publications
catogories: 
    - conference
permalink: /publication/2026-05-conference-AudioHijack-sp
#excerpt: ''
date: 2026-05-20
venue: 'Proceedings of IEEE S&P'
#paperurl: 'http://lynnlilu.github.io/files/.pdf'
citation: 'Meng Chen, Kun Wang, <b>Li Lu</b>*, Jiaheng Zhang, Tianwei Zhang. &quot;Hijacking Large Audio-Language Models via Context-Agnostic and Imperceptible Auditory Prompt Injection.&quot; <i>Proceedings of IEEE S&P</i>. San Francisco, CA, USA. 2026. doi: to appear.'
---

IEEE Symposium on Security and Privacy is the premier forum for presenting developments in computer security and electronic privacy, and for bringing together researchers and practitioners in the field. IEEE S&P is a Top-four security and CCF-A conference.

Abstract: Modern Large audio-language models (LALMs) power intelligent voice interactions by tightly integrating audio and text. This integration, however, expands the attack surface beyond text and introduces vulnerabilities in the continuous, high-dimensional audio channel. While prior work studied audio jailbreaks, the security risks of malicious audio injection and downstream behavior manipulation remain underexamined. In this work, we reveal a previously overlooked threat, auditory prompt injection, under realistic constraints of audio data-only access and strong perceptual stealth. To systematically analyze this threat, we propose AudioHijack, a general framework that generates context-agnostic and imperceptible adversarial audio to hijack LALMs. AudioHijack employs sampling-based gradient estimation for end-to-end optimization across diverse models, bypassing non-differentiable audio tokenization. Through attention supervision and multi-context training, it steers model attention toward adversarial audio and generalizes to unseen user contexts. We also design a convolutional blending method that modulates perturbations into natural reverberation, making them highly imperceptible to users. Extensive experiments on 13 state-of-the-art LALMs show consistent hijacking across 6 misbehavior categories, achieving average success rates of 79%–96% on unseen user contexts with high acoustic fidelity. Real-world studies demonstrate that commercial voice agents from Mistral AI and Microsoft Azure can be induced to execute unauthorized actions on behalf of users. These findings expose critical vulnerabilities in LALMs and highlight the urgent need for dedicated defense.

[View the full paper](https://lynnlilu.github.io/files/26-AudioHijack-SP.pdf)
