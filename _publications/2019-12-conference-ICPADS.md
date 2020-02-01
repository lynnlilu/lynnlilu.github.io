---
title: "Dynamically Adjusting Scale of a Kubernetes Cluster Under QoS Guarantee"
collection: publications
catogories: 
    - conference
permalink: /publication/2019-12-conference-ICPADS
#excerpt: ''
date: 2020-01-30
venue: 'The 25th International Conference on Parallel and Distributed Systems (IEEE ICPADS 2019)'
#paperurl: 'http://lynnlilu.github.io/files/VPad.pdf'
citation: 'Qiang Wu, Jiadi Yu, Li Lu, Shiyou Qian, Guangtao Xue. (2019). &quot; Dynamically Adjusting Scale of a Kubernetes Cluster Under QoS Guarantee.&quot; <i>IEEE ICPADS 2019</i>. Tianjin, China. pp. 193-200. doi: 10.1109/ICPADS47876.2019.00037'
---

IEEE ICPADS is a CCF-C conference.

Abstract: Nowadays, the container-based virtualization technologies have become very popular due to lightweight nature, scalability, flexibility and others. Kubernetes is one of the most popular container cluster management systems, which enables users to deploy applications on the container easily, so more and more web applications are deployed in a Kubernetes clusters. However, a Kubernetes cluster is generally designed to handle the peak of workloads, so that most of resources are idle in usual time, which results in an huge waste of resource. Hence, it is necessary to design a system to improve the cluster resource utilization and promise Quality of Service (QoS) in a Kubernetes cluster. In this paper, we propose a generic system to dynamically adjust the scale of a Kubernetes cluster, which is able to reduce the waste of resource on the premise of QoS guarantee. The proposed system contains four modules: monitor module, QoS module, scaling module, and executing module. First, the monitor module uses two open-source tools, Heapster and InfluxDB, to monitor and store real-time status of a Kubernetes cluster. Then, to guarantee QoS in the Kubernetes cluster, the QoS module presents a method to automatically decide a threshold of CPU utilization that is able to meet requirements of a specific application. Next, the scaling module provides a cluster scaling algorithm to get an ideal number of nodes in the Kubernetes cluster, which is used to allocate resources in a cluster-level allocation. Finally, according to the ideal number of nodes, the executing module adjusts the scale of the Kubernetes cluster to carry out the application. Extensive experiments in real environments show that, on average, the proposed system improves CPU utilization of a Kubernetes cluster by 28.99%.

[View the full paper](https://www.doi.org/10.1109/ICPADS47876.2019.00037)

