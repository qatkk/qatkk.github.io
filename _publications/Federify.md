---
title: "Federify: A Verifiable Federated Learning Scheme Based on zkSNARKs and Blockchain"
collection: publications
category: manuscripts
permalink: /publication/Federify
excerpt: 'Federify is a decentralized federated learning framework that uses blockchain, homomorphic encryption, and zero-knowledge proofs to ensure privacy, security, and transparency without relying on a central server.'
date: 2023-12-25
venue: 'IEEE Access'
slidesurl: 'https://www.youtube.com/watch?v=G8V6AhnDBoA'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10373785'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Federated learning (FL) has emerged as an alternative to traditional machine learning in scenarios where training data is sensitive. In federated learning, training is held at end devices, and thus data does not need to leave users’ devices. However, most approaches to federated learning rely on a central server to coordinate the learning process which, in turn, introduces its own security and privacy problems. We propose Federify, a decentralized federated learning framework based on blockchain that employs homomorphic encryption and zero knowledge proofs to provide security, privacy, and transparency. The scheme successfully preserves the confidentiality of both the data used for training and the local models using homomorphic encryption. All model parameters are publicly verifiable using zkSNARKs, and transparency of both the learning process and the incentive mechanism is achieved by delegating coordination to a public blockchain. The evaluation of the proof of concept of our framework demonstrates its viability both in terms of required computational resources and the cost to train on a public generic blockchain such as Ethereum.
