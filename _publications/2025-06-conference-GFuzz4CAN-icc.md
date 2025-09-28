---
title: "GFuzz4CAN: A Generative Model-based Fuzzing Method for In-vehicle Controller Area Network"
collection: publications
catogories: 
    - conference
permalink: /publication/2025-06-conference-GFuzz4CAN-icc
#excerpt: ''
date: 2025-06-09
venue: 'Proceedings of IEEE ICC'
#paperurl: 'http://lynnlilu.github.io/files/.pdf'
citation: 'Yuhan Wu, <b>Li Lu</b>*, Yuli Wu, Shuguo Zhuo, Zhan Qin, Kui Ren. &quot;GFuzz4CAN: A Generative Model-based Fuzzing Method for In-vehicle Controller Area Network.&quot; <i>Proceedings of IEEE ICC</i>. Montreal, Canada. 2025. doi: 10.1109/ICC52391.2025.11160828.'
---
This work received the Best Paper Award of IEEE ICC 2025.

IEEE International Conference of Communications is the flagship conference of IEEE Communications Society. IEEE ICC is a CCF-C conference.

Abstract: Controller Area Network (CAN) bus has been the fundamental communication method to interconnect the critical powertrain and body domains in vehicles for decades. Typical in-vehicle CAN buses employ rule-based Intrusion Detection Systems (IDS) to prevent non-compliant CAN messages for security enhancement. However, as the progress of connected autonomous vehicular techniques, more undiscovered vulnerabilities behind CAN IDS are gradually exposed, causing severe threats to vehicle safety, even threatening human life. To address it, fuzzing has become an efficient security testing method to automatically explore unknown vulnerabilities underlying the in-vehicle CAN bus. Existing fuzzing methods either conduct time-consuming random testing that is easily detected by IDS, causing inefficient vulnerability exploration, or rely on precious expert experience for higher efficiency. Instead, this paper turns to seek the power of deep generative models that automatically learn the data communication protocol for compliant fuzzing sample generation. Such a method both releases the experts' knowledge of reverse engineering, and can generate compliant samples to bypass typical rule-based IDS. To further improve the efficiency of exploring exceptions based on the generated samples, we optimize the reward function of SeqGAN with Extreme Value Theory (EVT), to fit the distribution of exception samples. With the trained model, we design a fuzzing system GFuzz4CAN, and conduct extensive experiments for evaluation. Experimental results on open-source datasets and a CAN bus device demonstrate that GFuzz4CAN can achieve 2~11x higher efficiency compared to byte-level random fuzzing, and is feasible to identify 2 vulnerabilities on the device.

[View the full paper](https://www.doi.org/10.1109/ICC52391.2025.11160828)
