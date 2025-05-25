---
title: "Cloud Native AI Training with Kubernetes"
date: 2024-04-15
draft: false
tags: ["Kubernetes", "AI", "OpenSource", "AIInfrastructure", "Innovation", "CloudNativeAI"]
categories: ["Cloud Computing", "DevOps", "Containerization"]
summary: "Kubernetes is increasingly the standard for AI workloads, driven by its open-source ecosystem and centralized management."
---

At KubeCon Paris, there were many presentations on how Kubernetes is for AI and how Kubernetes is the API server and control plane managing AI workloads.

HPC is still relevant in large-scale computing (CFD, genome sequencing, weather simulation, etc) and Kubernetes will be different for AI. Both are converging rapidly as seen in KubeCon Paris. Kubernetes is not just a container orchestration platform but part of a larger CNCF ecosystem. The extensive ecosystem and community within the CNCF are key factors propelling the adoption of Kubernetes in today’s data centers and AI applications.

While Kubernetes is a powerful tool, it was initially designed for stateless applications. However, Kubernetes is steadily evolving to become the control plane for AI. 

Let's explore further on the following:

🌐 Open source: Both HPC and Kubernetes are driven by open-source and are the common thread that brings Kubernetes, HPC, and AI together. While HPC still has its place in large-scale computing, Kubernetes is a part of the CNCF family and is backed by a huge open-source community. 

⚒️ Developers and Engineers: Large pool of certified Kubernetes talents, such as CKA, CKS and CKAD to build and maintain your AI platforms. HPC engineers are kind of hard to find nowadays. Most fresh graduates that I talk to are either working or learning Kubernetes. Remember OpenStack?

🚀 Standard Operating Platform: Every HPC system in the world is built slightly differently. Kubernetes is the standard orchestration layer between your servers and your AI jobs. It has extensibility that is built into the platform by the community. I even call Kubernetes the “Cloud Operating System” because everything goes through the Kubernetes API server. 

🧰 Toolchain in Kubernetes: You can now use common tools like Prometheus, Argo Workflows, Loki and Grafana to monitor and manage your cluster. Yes, you could deploy Prometheus and Node Exporter on your baremetal Ubuntu boxes with Ansible/Puppet/xCat but why not just use Kubernetes and GitOps to do that for you? Let the resources be managed and governed by Kubernetes, which makes orchestration much more manageable. 

📊 Centralized management: By centralizing management on Kubernetes, you can simplify the interaction between different teams and benefit from Kubernetes’s patterns like Watch, Controllers, Reconciliation, CRD and more. 

🗓️ Job scheduler: Why not take advantage of the best of both words? Use an HPC scheduler like Slurm or IBM Spectrum LSF with Kubernetes to offer advanced scheduling capabilities. Or use a distributed computing in a cloud-native environment using CodeFlare and Ray Clusters.

Finally, 

❓ Is Kubernetes suitable for AI? Major players like OpenAI, CodeWeave and Nvidia have already embraced Kubernetes for large-scale AI training and leveraging the CNCF ecosystem. In the recent Nvidia GTC, Nvidia announced NIM (Nvidia Inference Microservices). NIM is a Docker container orchestrated by Kubernetes.

Kubernetes enables on-premises or cloud AI training testbeds, deep learning as a service (DLaaS), deployment of AI/ML applications, and seamless integration with Kubeflow or other tools for end-to-end ML pipelines. Kubernetes provides flexibility, scalability, and resource management for AI workloads, making it an excellent choice for training and deploying machine learning models. 

The next article will go into more in-depth on how you would use Kubernetes for large-scale AI training. 


