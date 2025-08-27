---
title: "Building Resilient AI: A Solution to Data and Model Poisoning Prevention"
collection: publications
category: conferences
permalink: /publication/Resilient-AI
excerpt: 'Authors: Ghazaleh Keshavarzkalhori, Cristina Perez-Solá, Guillermo Navarro-Arribas, Jordi Herrera-Joancomartí<br>
    A cryptography-based scheme using hashes, signatures, and zero-knowledge proofs is proposed to protect machine learning from data and model poisoning, ensuring secure and verifiable training.'
date: 2024-02-17
venue: '17th International Conference on Security of Information and Networks (SIN)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10871752'
---

In many machine learning scenarios, training occurs outside the control of the model sponsor or the entity using the model. A growing concern in such settings revolves around model poisoning and data poisoning-how training is conducted and which data contributes to the process. This paper introduces a protective scheme against model and data poisoning attacks. Leveraging cryptographic primitives such as hashes, signature schemes, and zero-knowledge proofs, the scheme ensures the integrity of the training process. Hashing maintains the continuity of data from authenticated sensors, while signatures validate the data. In the end, zero-knowledge proofs verify the correct model computation by the entity carrying out the training process. By adopting this approach, model sponsors can securely delegate training tasks, guaranteeing the authenticity of the results. Implementation and testing demonstrate the scheme's feasibility, effectively countering data and model poisoning threats.