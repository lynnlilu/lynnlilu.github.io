---
title: "Lip Reading-based User Authentication through Acoustic Sensing on Smartphones"
collection: publications
permalink: /publication/2019-01-LipPass-TON
#excerpt: ''
date: 2019-01-23
venue: 'IEEE/ACM Transactions on Networking'
#paperurl: 'http://lynnlilu.github.io/files/08486283-2.pdf'
citation: 'Li Lu, Jiadi Yu, Yingying Chen, Hongbo Liu, Yanmin Zhu, Linghe Kong, Minglu Li. (2019). &quot;Lip Reading-based User Authentication through Acoustic Sensing on Smartphones.&quot; <i>IEEE/ACM Transactions on Networking</i>. 28(1)'
---

IEEE/ACM Transactions on Networking is a top-level journal on computer networking and communications, which is co-sponsored by IEEE ComSoc, IEEE CS and ACM with SIGCOMM. IEEE/ACM ToN is a CCF-A journal.

To prevent users' privacy from leakage, more and more mobile devices employ biometric-based authentication approaches, such as fingerprint, face recognition, voiceprint authentications, and so on, to enhance the privacy protection. However, these approaches are vulnerable to replay attacks. Although the state-of-art solutions utilize liveness verification to combat the attacks, existing approaches are sensitive to ambient environments, such as ambient lights and surrounding audible noises. Toward this end, we explore liveness verification of user authentication leveraging users' mouth movements, which are robust to noisy environments. In this paper, we propose a lip reading-based user authentication system, LipPass, which extracts unique behavioral characteristics of users' speaking mouths through acoustic sensing on smartphones for user authentication. We first investigate Doppler profiles of acoustic signals caused by users' speaking mouths and find that there are unique mouth movement patterns for different individuals. To characterize the mouth movements, we propose a deep learning-based method to extract efficient features from Doppler profiles and employ softmax function, support vector machine, and support vector domain description to construct multi-class identifier, binary classifiers, and spoofer detectors for mouth state identification, user identification, and spoofer detection, respectively. Afterward, we develop a balanced binary tree-based authentication approach to accurately identify each individual leveraging these binary classifiers and spoofer detectors with respect to registered users. Through extensive experiments involving 48 volunteers in four real environments, LipPass can achieve 90.2% accuracy in user identification and 93.1% accuracy in spoofer detection.

[View full paper]{https://ieeexplore.ieee.org/document/8624590}

