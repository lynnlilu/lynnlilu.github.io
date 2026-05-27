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

This work was reported by [IEEE Spectrum](https://spectrum.ieee.org/voice-ai-audio-attacks) on May, 2026. We also have a live interview with [The Agenda of Dubaieye](https://omny.fm/shows/the-agenda-with-georgia-tolley/hottest-may-in-the-uae) to talk about this work.

Following this news, many media reprint the news to report our work. Parts of them are listed as follows.

1.	RobotToday，[“Voice AI Systems Are Vulnerable to Hidden Audio Attacks”](https://robottoday.com/industry-briefing/voice-ai-systems-are-vulnerable-to-hidden-audio-attacks/2209)

2. AI ForeSights, [“Voice AI Systems Are Vulnerable to Hidden Audio Attacks”](https://www.aiforesights.com/article/voice-ai-systems-are-vulnerable-to-hidden-audio-attacks-mpb3l8a6)

3. Ideaverse.ai, [“Hidden Audio Attacks: How Voice AI Can Be Hijacked by Inaudible Signals”](https://ideaverse.ai/blog/hidden-audio-attacks-how-voice-ai-can-be-hijacked-by-inaudible-signals-mpbozvq4)

4. Futurism, [“Hackers Find That Inaudible Sounds Hidden in Podcasts or Random Videos Can Hijack Your AI Voice Chatbot”](https://futurism.com/artificial-intelligence/hackers-inaudible-recordings-hijack-ai-voice-chatbots)

5. Cybernews, [“AI voice assistances hijacked by hidden audio commands”](https://cybernews.com/security/ai-voice-bots-hidden-audio-hijack-attacks)

6. 新浪科技, [“语音 AI 系统易遭受隐秘音频攻击”](https://finance.sina.com.cn/tech/roll/2026-05-19/doc-inhymivk0030928.shtml)

IEEE Symposium on Security and Privacy is the premier forum for presenting developments in computer security and electronic privacy, and for bringing together researchers and practitioners in the field. IEEE S&P is a Top-four security and CCF-A conference.

Abstract: Modern Large audio-language models (LALMs) power intelligent voice interactions by tightly integrating audio and text. This integration, however, expands the attack surface beyond text and introduces vulnerabilities in the continuous, high-dimensional audio channel. While prior work studied audio jailbreaks, the security risks of malicious audio injection and downstream behavior manipulation remain underexamined. In this work, we reveal a previously overlooked threat, auditory prompt injection, under realistic constraints of audio data-only access and strong perceptual stealth. To systematically analyze this threat, we propose AudioHijack, a general framework that generates context-agnostic and imperceptible adversarial audio to hijack LALMs. AudioHijack employs sampling-based gradient estimation for end-to-end optimization across diverse models, bypassing non-differentiable audio tokenization. Through attention supervision and multi-context training, it steers model attention toward adversarial audio and generalizes to unseen user contexts. We also design a convolutional blending method that modulates perturbations into natural reverberation, making them highly imperceptible to users. Extensive experiments on 13 state-of-the-art LALMs show consistent hijacking across 6 misbehavior categories, achieving average success rates of 79%–96% on unseen user contexts with high acoustic fidelity. Real-world studies demonstrate that commercial voice agents from Mistral AI and Microsoft Azure can be induced to execute unauthorized actions on behalf of users. These findings expose critical vulnerabilities in LALMs and highlight the urgent need for dedicated defense.

[View the full paper](https://lynnlilu.github.io/files/26-AudioHijack-SP.pdf)
