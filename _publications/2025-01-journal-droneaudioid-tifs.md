---
title: "DroneAudioID: A Lightweight Acoustic Fingerprint-Based Drone Authentication System for Secure Drone Delivery"
collection: publications
catogories: 
    - journal
permalink: /publication/2025-01-journal-droneaudioid-tifs
#excerpt: ''
date: 2025-01-04
venue: 'IEEE Transactions on Information Forensics and Security'
#paperurl: 'http://lynnlilu.github.io/files/.pdf'
citation: 'Meng Zhang, <b>Li Lu</b>*, Yuhan Wu, Zheng Yan, Jiaqi Sun, Feng Lin, Kui Ren. &quot;DroneAudioID: A Lightweight Acoustic Fingerprint-Based Drone Authentication System for Secure Drone Delivery.&quot; <i>IEEE Transactions on Information Forensics and Security</i>. 2025. doi: 10.1109/TIFS.2025.3527814.'
---

IEEE Transactions on Information Forensics and Security is a premier journal on information security and signal processing, which is sponsored by IEEE Signal Processing Society. IEEE TIFS is a CCF-A journal.

Abstract: With the increasing accessibility of drones, they have been warmly embraced across various sectors, especially in low-altitude logistics transportation. However, during drone delivery, legal drones dispatched by logistics companies are susceptible to malicious attacks, resulting in package theft or substitution. To address this, existing works focus on designing drone authentication to secure drone delivery. However, most of these methods require expensive specialized equipment, such as high-quality microphones and professional recording devices, resulting in high real-world application costs. In this paper, we propose DroneAudioID, a lightweight acoustic fingerprint-based drone authentication system that relies solely on common mobile devices. The basic idea is to employ acoustic fingerprints to authenticate different drones of the same model based on differences in fundamental frequency and harmonic components of drone audio. Specifically, the drone audio is recorded by a mobile device instead of sophisticated equipment. We apply wavelet transform to remove high-frequency noise during data preprocessing. Then, specialized filter banks are designed for feature extraction, leveraging the frequency characteristics of drone audio. Finally, we construct a Bi-Long Short-Term Memory (Bi-LSTM) with an Open-Max model for open-set classification. Extensive experiments are conducted on eight crafts drones of DJIM ini2, showing an authentication accuracy of 99.6%. A series of comprehensive experiments further validate DroneAudioID's capability to defend against various attacks

[View the full paper](https://www.doi.org/10.1109/TIFS.2025.3527814)
