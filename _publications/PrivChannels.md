---
title: "Privacy in Lightning Network Channel Announcements"
collection: Projects
category: Projects
permalink: /publication/PrivChannels
excerpt: 'Master Thesis Project'
date: 2025-09-09
venue: 'UPC'
paperurl: 
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Bitcoin suffices the needs for the digital currencies to a high extent, but faces scalability challenges due to limited transaction throughput. Solutions like the Lightning Network aim to address this by enabling secure off-chain transacting, increasing throughput, and enhancing user privacy. However, the process of creating a payment channel and announcing it in the Lightning network—where users reveal details about locked funds and public keys—introduces potential privacy leaks. This creates a tension between maintaining the efficiency and cost-effectiveness of transacting funds and preserving user privacy.

This project investigates existing schemes approaching to enable private yet verifiable channel announcements in the Lightning Network. We evaluate these methods based on their privacy guarantees, trust assumptions, and practical applicability. Building on this analysis, we propose our scheme that combines the UTreeXO framework for efficient UTXO set verification with zkSNARKs adapted for the Bitcoin curve. Our approach improves verification efficiency while maintaining privacy and presents a proof-of-concept implementation to demonstrate its feasibility in real-world scenarios.


Please find the presentation [here](/files/TFM_presentation.pdf) 