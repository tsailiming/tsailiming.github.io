---
title: "AI is a Hybrid Cloud Workload"
date: 2024-03-30
draft: false
Tags: ["AI", "Hybrid Cloud", "Cloud Native", "Scalability", "Edge Computing", "Data Privacy", "Sustainability"]
Categories: ["Artificial Intelligence", "Cloud Computing", "Data Management"]
Summary: AI is a hybrid cloud workload, adopting cloud-native principles for efficiency and scalability.
---

AI is not new, but we are now at an AI revolution aka the “IPhone moment for AI”. As such, AI is rapidly becoming a more integral part of the technology landscape and as businesses seek to leverage AI capabilities, the question of where to deploy AI workloads becomes crucial. A hybrid cloud approach, which combines private cloud and public cloud services, is now a necessity for AI.

AI workload needs to adopt cloud-native principles because AI is not developed, trained and deployed within a single location. Recently, a CNCF’s working group published a new Cloud Native Artificial Intelligence Whitepaper. By combining AI and cloud-native technologies allows organizations to tap on cloud-native principles such as scalability and portability to deploy AI workload at scale.

Cloud Native Artificial Intelligence (CNAI) refers to approaches and patterns for building and deploying AI applications and workloads using the principles of Cloud Native. Enabling repeatable and scalable AI-focused workflows allows AI practitioners to focus on their domain.
Let's explore a few points on why AI is inherently a hybrid cloud workload.

## Scalability and Flexibility

AI applications often require vast amounts of computational power, particularly during the training phase of machine learning models. A hybrid cloud environment offers the scalability necessary to accommodate these fluctuating demands. Organizations have the flexibility to utilize on-premises resources or tap on cloud bursting for additional computing power. This allows them to keep the base workload on-premises and pay only for cloud resources when needed. 

## Inferencing at the Edge

Latency is an important consideration for AI workloads, especially when they involve real-time processing. Inferencing might be conducted at the edge, which is nearer to the data source, whether it is on a lamppost or a drone. Critical data can be processed and analyzed on-premises to ensure quick response times, while less time-sensitive tasks are offloaded to the on-premises data center or a public cloud.

## Green Data Centers

Many public cloud providers are investing in green data center technologies, using renewable energy sources and optimizing their infrastructure for minimal environmental impact. By selectively storing and processing data in these green public clouds, organizations can reduce their carbon footprint while maintaining control over their private data. As such, organizations with sustainability initiatives will want to have the option to train their model on green data centers and deploy their model somewhere else. 

Fun fact: Do you know that Singapore (ap-southeast-1) is not one of the greenest data centers in AWS because Singapore uses natural gas? Canada/Montreal has the lowest carbon emission per kwh.

## Data Privacy, Compliance and Gravity

Frequently, organizations must adhere to data privacy regulations, which often entails being near to the data’s location. Hybrid clouds allow businesses to retain their most sensitive data either on-premises or within a private cloud, granting them greater control over security and compliance. AI to the data and not data to the AI. 

## Conclusion

AI is a workload and should be treated like any other enterprise workload. Organizations no longer confine their AI development to a single data center. Instead, it spans across hybrid cloud environments, hence it is a hybrid cloud workload. To ensure efficiency and scalability, AI workloads should embrace cloud-native principles, enabling deployment and scaling wherever the business demands.