---
title: "Reimagining Proof-of-Work with Elliptic Curve Discrete Logarithms"
collection: publications
category: conferences
permalink: /publication/ECDLP_PoW
excerpt: 'Authors: Ghazaleh Keshavarzkalhori, Biel Castellarnau, Jordi Herrera, Cristina Perez <br>
   This is an attempt to evaluate/design a potential proof of work algorithm using discrete logarithm as the '
date: 2026-03-18
venue: 'XVIII Reunión Española sobre Criptología y Seguridad de la Información'
---
Proof-of-work (PoW) mechanisms enable a prover to present evidence of having performed a prescribed amount of computational effort. Asymmetry is at the core of proof-of-work design: verification of the performed work is highly efficient, whereas generating it requires substantially greater computational cost.

Although PoW is now predominantly associated with blockchain consensus protocols, the concept predates blockchain applications and was originally proposed in the context of mitigating abuse in distributed systems, such as spam prevention and access throttling.

Most existing PoW constructions employ cryptographic hash functions as their core computational task. These designs benefit from well-understood security properties and straightforward verification. However, hash-based schemes inherently require computations with no value beyond the proof itself. This characteristic has motivated research into PoW mechanisms that introduce additional structure or potential utility, while retaining the asymmetry required for practical deployment.

In this work, we examine the abstract properties that a generic PoW scheme must satisfy and explain how these properties manifest in the context of blockchain systems. Based on this analysis, we propose a new PoW construction derived from the Elliptic Curve Discrete Logarithm Problem (ECDLP). The scheme retains efficient verification and satisfies the properties necessary for blockchain mining.

The contributions of this paper are thus the enumeration of the requirements for PoW mechanisms in blockchain-specific contexts, the design of a scheme instantiated from ECDLP that meets these requirements, and the analysis of the limitations of this design.

Please find the paper [here](/files/RECSI2026___DLP_based_proofs_of_work.pdf) 